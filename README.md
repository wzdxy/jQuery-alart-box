#基于jQuery和BootStrap的弹出框插件
##1、Demo
http://wzdxy.github.io/alarm-box/
##2、依赖的文件
- jQuery.js
- Bootstrap.css
- alarm-box.js
- alarm-box.css

##3、使用方法
```js
createPopBox(str,title);
```
##4、接收的参数

`str` 通知正文，字符串或对象

`title` 通知标题，字符串

##5、配置(可选)
```js
ModalOptions={
    modalHeight:140,                    //每个modal的高度
    modalWidth:400,                     //每个modal宽度
    maxNum:3,                           //显示的modal数量
    modalTitle:'test title',            //标题
    bottomHeight:0,                     //modal距离底部的高度
    modalHeaderHeight:30,               //标题高度
    modalMargin:4,                      //modal的上下margin值
    btnInnerFirst:'忽略',               //第一个button的内容
    btnInnerSecond:'了解',              //第二个button的内容
}
initModal(ModalOptions);
```
###或
```js
ModalOptions.modalHeight=140;
ModalOptions.modalMargin=1;
initModal(ModalOptions);
```
###所有配置项均为可选项，可以随意选择配置其中的几项