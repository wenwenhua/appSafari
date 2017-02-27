# appSafari
IOS的Safri浏览器往上滑动网页的时候，正常布局的网页会隐藏地址栏和工具栏。
![image](https://github.com/wenwenhua/appSafari/raw/master/images/EG170226001.png) 
（地址栏和工具栏正常）
![image](https://github.com/wenwenhua/appSafari/raw/master/images/EG170226002.png) 
（地址栏变小，工具栏隐藏）
为了让Safari浏览器不隐藏工具栏和地址栏，布局时要使 html/body 的 高度为0，简单来说就是再里面设置一个 position:absolute 的 div，然后将内容都放置在这个 div 下。
