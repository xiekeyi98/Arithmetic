# Arithmetic
## 基础算法
1.模拟

2.乱搞

3.贪心

## 搜索
1.普通搜索

    1.BFS

    2.DFS
    
    3.双向BFS

2.搜索优化
    1.可行性剪枝

    2.最优性剪枝

    3.分支定界

    4.**meet in the middle**

3.智能搜索

    1.A*搜索

    2.粒子群优化算法

    4.蚁群算法

    5.遗传算法

    6.禁忌搜索算法

4.其他

    1.DLX

    2.迭代加深搜索

    3.LEXBFS

    4.**记忆化搜索**

## 分治

1.**CDQ**

2.**平面最近点对**

3.**二分**

4.**三分**

5.**整体二分**

## 排序算法

1.选择排序

2.快速排序

3.随机快速排序

4.归并排序

5.希尔排序

6.计数排序

7.基数排序

8.桶排序

## 动态规划

1.基本DP

2.DP优化

    1.滚动数组

    2.**单调队列**

        1.斜率优化

        2.四边形不等式

        3.决策单调性

        4.加速状态转移

    3.动态凸壳

    4.数据结构优化

3.**数位DP**

4.**状态压缩DP**

    1.插头DP

    2.轮廓线DP

5.**树形DP**

    1.树形DP

    2.外向树DP

    3.仙人掌图DP

    4.trie DP

    5.虚树 DP

## 图论

1.图的存储方式

    1.邻接矩阵

    2.邻接表

    3.链式前向星

2.Havel-Hakimi定理

3.活动网络

    1.AOV网络

    2.**拓扑排序**
    3.AOE网络

    4.逆拓扑排序

4.**生成树**

    1.树的存储

    2.最小生成树

        1.kurskal

        2.prim

        3.堆优化的prim

    3.次小生成树

    4.最优比例生成树

    5.最小树形图

    6.斯坦纳树

5.**最短路径**

    1.dijkstra

    2.堆优化的dijkstra

    3.Bellman-Ford

    4.SPFA

    5.Floyed

    6.Floyed求最小环

    7.Johnson算法

    8.差分约束系统

6.可行遍性

    1.欧拉回路

    2.汉密尔顿回路

7.**网络流**

    1.网络最大流

        1.最大流最小割定理

        2.Ford-Fulkerson算法

        3.Edmonds-Karp算法

        4.最短增广路算法

        5.连续最短增广路算法-dinic算法

        6.一般预流推进算法

        7.最高标号预流推进算法

        8.SAP算法

        9.建立平面对偶图，建立超级源点汇点，最短路径

    2.流量上下界的最大流和最小流

    3.最小费用最大流

        1.最短路增光费用流

        2.zkw费用流

    4.流量上下界的最小费用最大流

    5.经典模型

        1.最大权闭合子图

        2.最大密度子图

        3.不等式转换

        4.动态流

8.**支配集.覆盖集.独立集与匹配**

    1.点支配集.点覆盖集.点独立集概念及求解

    2.边支配集.边覆盖集.边独立集概念及求解

    3.匹配问题

        1.匈牙利算法

        2.网络流算法

        3.KM算法

        4.最小覆盖

        5.最大独立集

        6.最小路径覆盖

        7.HK算法

     4.稳定婚姻问题

9.**图的连通性**

    1.无向图的割顶和桥

    2.有向图的割顶和桥

    3.有向图强连通分量

        1.Tarjan算法

        2.Kosaraju算法

        3.Gabow算法

    4.强连通分量

        1.缩点

        2.2-SAT

10.平面图及图的着色问题

    1.平面图与对偶图

    2.欧拉公式

    3.泛性平面图判定

    4.图的着色问题

        1.五色定理

        2.区间图.弦图.完美图

11.**第K小问题**

    1.第K短路

    2.第K小生成树

    3.第K小割

## 数学

1.**数论** 

    1.gcd

    2.extended_gcd

    3.中国剩余定理

        1.中国剩余定理

        2.扩展中国剩余定理

    4.欧拉函数

    5.Miller-rabin素性测试

    6.进制转换

    7.Pollard-rho整数分解

    8.狄利克雷卷积函数

    9.欧拉筛

    10.O（n）求phi

    11.O（n）求逆元

    12.离散对数

        1.Baby Step Giant Step

        2.扩展Baby Step Giant Step

    13.费马小定理.欧拉定理

    14.lucas定理

        1.lucas定理

        2.扩展lucas定理

    15.N的约数的欧拉函数之和=N

    16.莫比乌斯反演

    17.原根

        1.求指数

        2.求原根

    18.Stern-Brocot tree与Farey序列

    19.n次剩余

        1.平方剩余

        2.n次剩余

    20.整点问题

    21.不定方程

2.**组合数学**

    1.计数原理

        1.组合数递推求解

        2.母函数

        3.群论

            ①置换群

            ②burnside引理

            ③Ploya原理

        4.Catalan数   

        5.Stirling数

        6.容斥原理

        7.鸽巢原理

        8.二项式定理

        9.康拓展开

    2.**博弈论**

        1.SG函数

        2.Nim游戏

        3.博弈树

    3.线性代数

        1.矩阵运算

            1.求解线性方程组

            2.矩阵求逆

            3.对称正定矩阵和最小二乘估计

            4.**高斯消元**

            5.矩阵乘法

                    Strassen算法

            6.矩阵倍增

        2.线性规划

            1.单纯形算法

            2.对偶问题

            3.**半平面交**

        3.**FFT与NTT**

        4.多项式求逆.多项式除法.牛顿迭代

    4.高等数学

        1.牛顿迭代

        2.微积分

        3.自适应simpson

        4.拉格朗日插值

    5.概率论

    6.其他

        1.配极

        2.高精度运算

        3.四位一存高精度

        4.快速幂

            1.二进制快速幂

            2.十进制快速幂

        5.快速乘

## 数据结构

1.线性表

    1.数组

    2.链表

    3.双向链表

    4.关联数组

    5.集合

    6.散列表

    7.**树状数组**

    8.块状链表

2.栈

    1.自然栈

    2.人工栈

    3.**单调栈**

3.队列

    1.普通队列

    2.**优先队列**

    3.循环队列

    4.**单调队列**

    5.Small label first

4.跳跃链表

3.树

    1.线段树

        1.**普通线段树**

        2.ZKW线段树

        3.多维线段树

        4.**函数式线段树（主席树）**

    2.二叉树

    3.自平衡二叉查找树

        1.AA树

        2.AVL树

        3.红黑树

        4.SBT

    4.伪平衡树

        1.伸展树

        2.替罪羊树

        3.朝鲜树

        4.**treap**

    5.空间划分树

        1.**K-D树**

        2.R树

    6.Van Emde Boas tree

    7.**树套树**

    8.**树上分治**

        1.**点分治**

        2.**边分治**

            ①树链剖分

            ②动态树

        3.euler tour tree

        4.top tree  

    10.**LCA**

        1.倍增

        2.DFS序

        3.Tarjan

    11.灭绝树

    12.块状树

4.堆

    1.普通堆

        1.小根堆

        2.大根堆

    2.可合并堆

        1.**左偏树**

        2.配对堆

        3.二项堆

        4.斐波那契堆

        5.斜堆

   3.其他

        随机堆

   5.**Hash**

   6.**并查集**

       1.路径压缩

       2.按秩合并

   7.**可持久化数据结构**

       1.可持久化线段树

       2.可持久化并查集

              1.链表覆盖

              2.线段树实现

       3.可持久化trie

       4.可持久化左偏树

       5.可持久化AVL

       6.可持久化treap

       7.可持久化替罪羊树

       8.可持久化凸包

       9.可持久化树状数组

       10.可持久化块状链表

       11.可持久化动态树

       12.可持久化数据结构套可持久化数据结构



## 字符串算法

1.**manacher**

2.**Trie树**

3.**AC自动机**

4.后缀树

5.**后缀数组**

6.后缀自动机

7.后缀平衡树

8.**KMP**

9.**扩展KMP**

10.前缀树

11.回文自动机



## 计算几何

1.向量

2.旋转公式

3.**极角排序**

4.线段.直线.多边形求交

5.圆
    1.求切线

    2.求交

6.**凸包**

    1.二维

    2.三维

7.**半平面交**

8.**旋转卡壳**

9.随机增量

10.平面图求域

11.Voronoi图

12.**三角剖分**

13.点定位

14.平面曼哈顿最小生成树

15.反演变换

16.仿射法

17.扫描法


## 其他

1.爬山法

2.随机增量法

3.扫描线

4.**倍增(Sparse Table)**

5.**离线**

    1.莫队算法

    2.树上莫队算法

6.漂浮法

7.Floyd判环

