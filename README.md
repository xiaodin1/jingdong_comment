# jingdong_comment

简介： 自动进入京东小米,华为，iphone，sanmsung自营店，获得全部商品 id，并对每天更新的评论进行爬虫，删除相连的重复项。还需要多爬取增加用户信息等。

(5.3 更新： 改变爬虫代码，不用删除相邻重复项，新增赞数，追评等信息）

(5.4 更新： 重复项还是要删除，del.py效率不高，虽然只用一次，但不是最优方案。可以考虑用 SQL 进行删除操作）

(5.5 更新： 更新 level 正则表达式，更新更新代码）

(5.7 更新： 更新update错误，设定休眠时间，解决商品 ID 可能存在的乱码问题）

(5.8 问题： 首先是否应该一次性写入 mysql 而不是每次爬取后写入，其次如何解决网络波动问题）

(5.11 更新： 更新荣耀手机信息）

(5.12 问题：更新新的评论时间过长，达到600min，容易出现网络问题，如何解决？)

(5.13 更新：  count.py 用于统计已有数据量)

(5.14 更新： 一次更新评论时间过长，分为两个脚本分别更新）

(5.16 更新： 更新数据库提交次数，解决 update 中 cut 可能不存在问题)

(5.17 更新：更新 del ，增加删除主键 del_id ，修改了 count 以正确计数.）
