# ANeko Home

ANeko Home 是参考zyyo主页风格，基于 Astro、Vue 和 Cloudflare Workers 构建的个人站点

## 功能特性

- **仪表盘**
- **导航**
- **相册**
- **博客**
- **邮箱**
- **网盘**
- **后台管理**

## 技术栈

- [Astro](https://astro.build) 7（SSR，Cloudflare adapter）
- [Vue](https://vuejs.org)
- [Cloudflare Workers](https://workers.cloudflare.com) 部署


## 目录结构

```
src/
├── components/      # Vue / Astro 组件
├── layouts/         # 页面布局（站点、工作台、博客）
├── pages/           # 路由页面
│   ├── admin/blog/  # 博客管理后台
│   ├── blog/        # 博客相关页面
│   ├── photos/      # 相册
│   ├── mail/        # 邮箱
│   └── drive/       # 网盘
├── plugins/         # remark 等 MD 插件
└── layouts/         # 布局
public/              # 静态资源
```

## License

[MIT](./LICENSE)