# Conch JavaScript Library

Conch 是一个功能丰富的 JavaScript 库，提供了浏览器检测、Cookie 管理、窗口调整等功能。

## 功能特点

- 浏览器环境检测
- Cookie 管理
- 窗口大小调整
- 图片懒加载
- QR Code 生成
- 剪贴板操作
- 主题切换
- 多选功能
- 下载功能
- 积分系统

## 安装

通过 jsDelivr CDN 引入：

```html
<!-- 引入主文件 -->
<script src="https://cdn.jsdelivr.net/npm/conch-js@1.0.0/js/conch.vip.js"></script>

<!-- 引入基础设置文件 -->
<script src="https://cdn.jsdelivr.net/npm/conch-js@1.0.0/js/conch.set.js"></script>

<!-- 引入 jQuery 依赖 -->
<script src="https://cdn.jsdelivr.net/npm/conch-js@1.0.0/js/jquery.min.js"></script>
```

## 使用方法

```javascript
// 浏览器检测
console.log(Conch.Browser);

// Cookie 操作
Conch.Cookie.Set('name', 'value', 7); // 设置 Cookie
Conch.Cookie.Get('name'); // 获取 Cookie
Conch.Cookie.Del('name'); // 删除 Cookie

// 窗口调整
Conch.Resize();
```

## 目录结构

```
conch-js/
├── js/
│   ├── conch.vip.js    // 主文件
│   ├── conch.set.js    // 基础设置
│   └── parts/          // 功能模块
├── css/                // 样式文件
├── fonts/             // 字体文件
├── img/               // 图片资源
├── layui/             // Layui 框架
└── pwa/               // PWA 相关
```

## License

MIT 