<h1 align="center">思政助手</h1>
<p align="center"><img src="https://img.shields.io/badge/version-1.0-red.svg"></p>

这是个人写的`政治知识点浏览`的微信小程序`demo`,完全使用微信小程序原生开发，数据库使用的云开发提供的服务(免去了写后端的麻烦)，如果你了解<a href="https://github.com/weilanwl/ColorUI" >colorUI</a>你会发现很多熟悉的东西，因为大部分前端都是用的他的hhh(救我🐕命）。这是一个初级项目，🤹‍♀️微信小程序开发新手🤹‍♀️，如果你有 `html` `css` `js` 前端基础那么你将很快上手，代码完全免费开源，代码写的有点糙，后期会慢慢封装变得简洁些（当然如果您能愉快的给一个Start就更好了❤😋）


### 完成度

这个项目是为了巩固小程序学习，本身功能比较简单单一，非常适合入门练习，有些页面的某些功能并没有开发出来，目前这个项目还在慢慢完善中


### 运行

* clone 代码带本地在微信开发者工具中导入项目即可
* 下载本项目的zip包，解压之后在微信开发者工具中导入即可
* 首页的新闻数据是请求的聚合数据API，这里需要申请得到一个key(因为有使用次数限制，我设置请求不到是从数据库里获取)
* 需要再service文件夹里的config.js 设置API地址，组件文件夹里的home里面添加key 和类别
* 数据库的数据和结构打包为json文件(DB文件夹目录)，一键导入就可以了 表名按云函数里面的名字自行创建
<P align="center">
<img src="http://www.sanshididi.xyz/xql/Main/assets/images/mini.png" />
</p>

### 注意

* 项目对数据库的请求均封装到了云函数里面，业务逻辑都是本地处理，确实我有点懒hhhhhh 运行起来很吃内存

### TODO
  - [√] 通过API获取新闻数据
  - [√] 对某个特定章节进行评论
  - [√] 对某个特定章节可以进行收藏
  - [√] 查看个人的浏览记录，收藏记录
  - [×] 广场交友🐛🐛🐛
  - [×] 回复评论
  - [×] 显示回复通知

  
> 当然还有很多的bug......未完待续

###  建议&联系

欢迎您的建议或者是提出Bug

  * 邮箱：1246984534@qq.com 你可以在这里联系我
