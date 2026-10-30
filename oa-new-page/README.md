# OA新建页面 · 移动端高保真 Demo

项目来自 ChatGPT「OA新建页面」中的「实现 Figma 移动端高保真 Demo」。这是一个可交互的移动端流程助手页面演示。

## 在线预览

[打开 OA新建页面演示](https://z792028131-png.github.io/spring-festival-card-entry-demo/oa-new-page/)

## 页面交互

- 输入想办理的事项并提交，页面显示本地演示反馈。
- 按分类筛选全部流程，搜索流程名称和说明。
- 收藏或取消收藏流程，反馈只保存在当前页面状态中。
- 页面以 402 px 设计宽度为基准，按浏览器宽度等比适配。

演示不连接实际 OA、审批系统或员工数据服务。

## 源码

- `source/`：React + Vite 源码与设计素材。
- `source.zip`：可下载的源码包，不包含 `node_modules` 和本地启动脚本。
- 发布版由 `source/` 执行 `pnpm build` 生成在当前目录根部。

项目首页：[交互原型库](https://z792028131-png.github.io/spring-festival-card-entry-demo/)。
