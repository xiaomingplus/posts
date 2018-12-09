# 一切以 git 为核心的网志管理系统

## 想法来源

我们的文章常常会散落在各个平台，极其的不好管理。

所以这个时候我就期待，有没有这样一个地方？

我把所有的文章都放在那里，在那里做一些配置，他就会在我发布之后，自动把我的文章发布到我要发布的平台，并且，如果我要发布的平台支持修改文章的话，那么后续我只需要在这个地方进行一次修改，其他所有的地方都能自动的触发相应的修改。

## 准备工作

开始做吧，目前先能支持自动同步到 twitter 和 medium，因为这两家的 api 给的足够的好，较容易做到。

## 目录结构设计

```shell
├── CONTRIBUTING.md
├── README.md
├── package.json
├── .gitpostsrc # gitposts配置文件
└── source
    ├── README.md
    ├── society
    │   ├── moral.md # 网志1
    │   └── profession.md # 网志2
    └── tech
        └── posts-base-git.md # 网志3
```

## 配置项

```yaml
# todo
```
