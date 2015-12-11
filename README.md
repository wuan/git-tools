# git-tools

## `git-stats`

### Usage

```
> git-stats <user-mapping> ...
```

where `<user-mapping>` is in the format `user:mapped_user` 

### Example
Create per user statistics like:

```
+-------+---------+---------+------------+-----------+-------+
| User  | Commits | Updates | Insertions | Deletions | Delta |
+-------+---------+---------+------------+-----------+-------+
| user1 |     338 |     828 |      12594 |      9024 |  3570 |
| user2 |      48 |      88 |       1178 |       714 |   464 |
| user3 |      36 |      88 |       1840 |       738 |  1102 |
| user5 |      34 |     101 |       3123 |      3067 |    56 |
| user4 |      22 |      30 |        399 |       309 |    90 |
| user6 |      13 |      40 |       2975 |       113 |  2862 |
| user7 |       4 |      10 |         35 |        90 |   -55 |
| TOTAL |     495 |    1185 |      22144 |     14055 |  8089 |
+-------+---------+---------+------------+-----------+-------+
```
