## 开发微信小程序技术调研 </br>
### 开发工具：微信开发者工具 </br>
整个小程序框架系统分为两部分：逻辑层（App Service）和 视图层（View）。小程序提供了自己的视图层描述语言 WXML 和 WXSS，以及基于 JavaScript 的逻辑层框架，并在视图层与逻辑层间提供了数据传输和事件系统，让开发者能够专注于数据与逻辑。</br>
### 框架对比与分析 </br>
### 框架 uni-app[https://uniapp.dcloud.io] </br>

1、 多端开发利器  uni-app 是一个使用 Vue.js 开发所有前端应用的框架，开发者编写一套代码，可发布到 iOS、Android、H5、以及各种小程序（微信 / 支付宝 / 百度 / 头条 /QQ/ 钉钉）等多个平台。即使不跨端， uni-app 同时也是更好的小程序开发框架。</br>
2、Taro[https://taro.aotu.io] 是一套遵循 React 语法规范的 多端开发 解决方案。

现如今市面上端的形态多种多样，Web、React-Native、微信小程序等各种端大行其道，当业务要求同时在不同的端都要求有所表现的时候，针对不同的端去编写多套代码的成本显然非常高，这时候只编写一套代码就能够适配到多端的能力就显得极为需要。多端开发支持：
- 微信小程序
- H5
- 百度小程序
- 支付宝小程序
- 快应用
- ReactNative
- 字节跳动小程序
- QQ 轻应用
### 小程序 UI 框架 [https://weui.io] </br>
WeUI 是一套同微信原生视觉体验一致的基础样式库，由微信官方设计团队为微信内网页和微信小程序量身设计，令用户的使用感知更加统一。对微信的支持是非常完美的，基本你想要的组件这里都能找到。
