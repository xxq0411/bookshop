# 知识点：
* string.split(""),将字符串分隔为数组，包括空格如：hover me ---["h","o","v","e","r","","m","e"]
* line-24-25
    top:50%;
    transform:translateY(-50%);
   作用相当于使元素垂直居中于页面。
   top的效果取决于元素的position属性（非定位元素该属性无效！）：   
   当position设置为absolute或fixed时，top属性指定了定位元素上外边距边界与其包含块上边界之间的偏移。
   当position设置为relative时，top属性指定了元素的上边界离开其正常位置的偏移。
   单位为百分比时代表元素包含块（即父元素，父元素未设置hight，top无效！）的高度的百分比。此例中text的包含块为body,高度为页面100%。
   所以top:50%，在此例中使元素上外边距位于页面50%处。
   transform:translateY(-50%);
   相对于Y轴向上垂直运动原位置元素高度的50%。
   
  * cursor,表示光标种类。
  
  * 当父元素未设置height时，子元素的height会将其撑开。
  
  * 选择器：
    #text .wrapper{
    }
    表示选择id=text的元素里class=wrapper的元素。
    #text .wrapper span .letter-1:hover ~ .letter-2 {
    }
    表示选择letter-1在hover状态下的所有letter-2的样式。
    
  * transition：以下四个属性的简写
  transition-property：设置过渡效果的 CSS 属性的名称
  transition-duration：设置过渡所需的时间
  transition-timing-function：速度曲线
  transition-delay：过度曲线何时开始；
  
  ？？？在备选元素的被选属性有新的值时会逐渐过渡到新的值。
  * array.map(function(){
  })
  该方法表示数组中的每一个元素都挨个经过map中的函数处理，得到一个新的数组
  
  * promise构造函数
  
  用于异步请求。先promise()
再than（）、再than（）；

此处用promise因为setTimeout()方法为异步方法。

  * setTimeout(),计数器
  在指定的毫秒数后调用函数
  
  * span.offsetWidth为可读属性，不能更改。
  通过JS设置的css属性皆为行内属性，具有css样式的最高权限
  
   