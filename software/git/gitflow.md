# Gitflow工作流
`Gitflow`工作流通过为功能开发、发布准备和维护分配独立的分支，让发布迭代过程更流畅。

## 分支
* `master` 可发布的内容
* `develop` 开发的分支。从`master`上fork,测试完成后，合并到`master`
* `feature-x` 某新特性的分支，从`develop`上`fork`,测试完成后，合并到`develop`
* `bugfix-x` 修复某bug的分支，从`develop`上`fork`,测试完成后，合并到`develop`

可以用这个工具来简化流程 [gitflow](https://github.com/nvie/gitflow)

## 拓展阅读
* [使用GIT FLOW管理开发流程](http://stormzhang.com/git/2014/01/29/git-flow/)
* [git-workflow-tutorial](https://github.com/xirong/my-git/blob/master/git-workflow-tutorial.md)
