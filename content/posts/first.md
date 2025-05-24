+++
date = '2025-05-21T12:15:45+08:00'
draft = false
title = '起点：博客配置与部署'
+++
> 本文记录使用 Hugo + PaperMod 主题搭建个人博客的完整过程与排版技巧，适合初学者快速上手。

---

##  一. 创建新文章

要创建一篇新的博客，首先需要回到根目录：
```bash
cd ~/my-site
```
然后执行：
```bash
hugo new posts/third.md
```
然后便可以用vim修改：
```bash
vim content/posts/third.md
```
或者用VS Code打开修改：
```bash
code content/posts/third.md
```

##  二. 界面技巧

1. 使用 '>' 给界面增加一个备注

2. 使用 '- - -' 给标题和正文之间增加一条线，保持美观

3. 改变文字的各种符号：

** 加粗内容 ** ：**内容**

\* 斜体内容 \* ：*内容*

~~ 删除线内容 ~~：~~内容~~

##  三. 网页部署
我们的部署采用Github Page
