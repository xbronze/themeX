

本主题为您提供了类别、标签和关于页面。但是还需要您在hexo项目的“source”文件夹中手动创建这些页面。

例如，要创建“类别”页面，您可以在 source 文件夹下创建 categories 文件夹，并在创建后的categories 文件夹中创建一个包含以下内容的 index.html 文件：

```
---
title: categories
date: 2023-08-07 20:07:28
type: "categories"
layout: "categories"
---

```

当然也可以通过命令快速创建：

```
hexo new page categories
```

“标签”和“关于”页面的创建步骤与“类别”一致，只不过是生成的index.html文件中，`type`和`layout`的值不同。

“标签”页的值是

```
type: "tags"
layout: "tags"
```

“关于”页的值是：

```
type: "about"
layout: "about"
```
