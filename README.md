# 晚霞 Afterglow

xyuntee 的个人主页，用来展示作品与整理知识笔记。

网站地址：https://xyuntee.github.io/

## 修改内容

这是一个无需安装依赖的静态网站。页面、样式与内容都在 `index.html` 中。

- 修改站名、个人介绍：在 `index.html` 中搜索“晚霞”或“你好，我是”。
- 修改知识笔记：搜索 `const entries = [`，编辑相应条目的标题、摘要、分类、日期和正文。
- 新增笔记：复制 `entries` 中一个条目，使用新的唯一 `id`，设置 `type: 'note'`。
- 新增作品：同样增加条目，设置 `type: 'project'`。
- 发布自己的内容时，将 `example` 改为 `false`。初始的三篇笔记均已明确标注为示例。
- 正文支持 `p`（段落）、`h3`（小标题）、`ul`（列表）、`quote`（引文）。
- `art` 可选 `study`、`create`、`collect` 三种内置插画。

在 GitHub 网页打开文件后，点击铅笔图标编辑，再点击 **Commit changes（提交更改）**。GitHub Pages 会重新发布。

## 本地查看

直接使用浏览器打开 `index.html`，即可查看。也可以用任何静态文件服务器预览。

## 发布配置

仓库名为 `xyuntee.github.io`。在 **Settings → Pages → Build and deployment** 中选择 **Deploy from a branch**，分支选择 `main`，文件夹选择 `/ (root)`。

## 功能

- 响应式布局，适配电脑与手机
- 全中文导航与内容
- 内容分类和全文关键词搜索
- 文章阅读弹窗，支持键盘关闭
- 深浅色主题切换，偏好保存于当前浏览器
- 无外部字体、统计脚本、登录服务或构建依赖
- 原创 SVG 插画

代码与网页内容为公开发布的文件；请只提交希望公开展示的资料。
