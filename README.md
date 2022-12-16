设计稿：[](https://lanhuapp.com/url/3xHFT-Jtw5j)

1、表单验证插件文档：[](https://ext.dcloud.net.cn/plugin?id=1137)
2、表单验证插件依赖async-validator，需要先npm install
3、hx-navbar 自定义导航栏插件
4、消息提示：this.$showToast('xxx', false) // 'xxx' 替换为提示内容，默认开启蒙版，设置false不开启
5、请求方法：
	otherConfig = { // 其他配置的默认值
		isFirst：true, // 是否需要token
		sucToast:false, // 请求成功的提示
		errToast: true, // 后端返回错误提示
	}
5.1 不带loading
	this.$get(url, data, otherConfig).then(res => {})
5.2、带loading
	this.$getLoading(url, data, otherConfig).then(res => {})

设置默认语言
main.js、fetch.js

打包的时候修改config.js里面的请求地址和store.js里面的baseUrl

malalike.com: 按固定
