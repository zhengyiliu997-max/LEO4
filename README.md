# 个人网站（可在 Cursor 中编辑）

这个项目已经整理成「可直接编辑 + 本地预览」的状态。

## 你要改哪里

主要改 `script.js` 顶部的 `profile` 对象（名字、邮箱、社交链接、关于我文案）：

- `name`：你的名字
- `title`：浏览器标签标题
- `description`：网页描述
- `roleLine1` / `roleLine2`：首页左下角文案
- `email` / `github` / `linkedin`：联系方式
- `about*`：ABOUT 面板中的内容

如果要改作品内容，修改 `script.js` 里的 `projects` 数组。

## 在 Cursor 里本地运行

在终端执行：

```bash
npm run dev
```

启动后打开终端输出中的本地地址（默认 `http://localhost:4173`）。

## 文件说明

- `index.html`：页面结构
- `styles.css`：样式与动画
- `script.js`：作品数据 + 页面交互 + 个人信息配置
