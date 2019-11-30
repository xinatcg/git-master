# git-master
A Git project to demo advance git operation


## Rebase

1. make branch `Feature1` and commit
2. create PR `Feature1` in github
3. make commit to `master`
4. rebase the `Feature1` to master
5. update the `Feature1`

## Squash and Rebase

Why Squash?

Because when rebase the feature branch to master, if you have conflict, you need to resolve it per every commit in the feature branch, so after squash you feature branch, you need only **resolve conflict one time**

1. make branch `Feature2` and commit
2. create PR `Feature2` in github
3. make commit to master
4. make some conflict between `Feature2` and `master`
5. squash and rebase the `Feature2` to `master` then resolve the conflict
6. update the `Feature`