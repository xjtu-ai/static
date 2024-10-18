## [Static files of AI Wiki](https://github.com/xjtu-ai/static)

这是 **[xjtu-ai.github.io](https://github.com/xjtu-ai/xjtu-ai.github.io)** 仓库的静态文件。请将 pdf 上传至此仓库。

此处的目录形式应该与 **[xjtu-ai.github.io](https://github.com/xjtu-ai/xjtu-ai.github.io)** 仓库中的 `docs` 文件夹一致。

当在此处上传文件后，最终的链接如下：此处的 `/course/a.pdf` 变化为 `https://xjtu-ai.github.io/static/course/a.pdf`。你应该在 Markdown 文件中用如下方式嵌入 pdf：

```markdown
??? note "a"
    <iframe loading="lazy" src="/static/course/a.pdf）"></iframe>
```
