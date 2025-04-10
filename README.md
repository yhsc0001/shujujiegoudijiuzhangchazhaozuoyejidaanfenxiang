# 数据结构第九章 查找作业及答案

## 资源文件

**文件名**: 数据结构第九章 查找作业及答案（100分）.docx

## 文件描述

本资源文件包含了数据结构第九章“查找”的作业题目及详细答案，涵盖了以下内容：

### 一、选择题（每题4分，共32分）

1. 对于二叉排序树，下面的说法（     ）是正确的。
   - A．二叉排序树是动态树表，查找不成功时插入新结点时，会引起树的重新分裂和组合
   - B．对二叉排序树进行层序遍历可得到有序序列
   - C．用逐点插入法构造二叉排序树时，若先后插入的关键字有序，二叉排序树的深度最大
   - D．在二叉排序树中进行查找，关键字的比较次数不超过结点数的1/2

2. 在有n个结点且为完全二叉树的二叉排序树中查找一个键值，其平均比较次数的数量级为（      ）。
   - A．O(n)
   - B．O(log2n)
   - C．O(n*log2n)
   - D．O(n2)

3. 静态查找与动态查找的根本区别在于（     ）。
   - A. 它们的逻辑结构不一样
   - B. 施加在其上的操作不同
   - C. 所包含的数据元素类型不一样
   - D. 存储实现不一样

4. 已知一个有序表为{12，18，24，35，47，50，62，83，90，115，134}，当折半查找值为90的元素时，经过（     ）次比较后查找成功。
   - A．2
   - B．3
   - C．4
   - D．5

5. 已知数据序列为（34，76，45，18，26，54，92，65），按照依次插入结点的方法生成一棵二叉排序树，则该树的深度为（      ）。
   - A. 4
   - B. 5
   - C. 6
   - D. 7

6. 设散列表表长m=14，散列函数H（k）=k mod 11 。表中已有15，38，61，84四个元素，如果用线性探测法处理冲突，则元素49的存储地址是（    ）。
   - A. 8
   - B. 3
   - C. 5
   - D. 9

7. 平衡二叉树的查找效率呈（    ）数量级。
   - A. 常数阶
   - B. 线性阶
   - C. 对数阶
   - D. 平方阶

8. 设输入序列为{201112…}构造一棵平衡二叉树，当插入值为12的结点时发生了不平衡，则应该进行的平衡旋转是（     ）。
   - A. LL
   - B. LR
   - C. RL
   - D. RR

### 二、填空题（每空3分，共24分）

1. 在有序表A[1..18]中，采用二分查找算法查找元素值等于A[7]的元素，所比较过的元素的下标依次为             。
2. 利用逐点插入法建立序列(61，75，44，99，77，30，36，45)对应的二叉排序树以后，查找元素36要进行     次元素间的比较，查找序列为                      。
3. 用顺序查找法在长度为n的线性表中进行查找，在等概率情况下，查找成功的平均比较次数是              。
4. 二分查找算法描述如下：
   ```c
   int Search_Bin(SST ST, KT key) {
       low = 1;
       high = ST.length;
       while (low <= high) {
           mid = (low + high) / 2;
           if (key == ST.elem[mid].key)
               return mid;
           else if (key < ST.elem[mid].key)
               ;
           else
               ;
       }
       return 0;
   }
   ```
5. 链式二叉树的定义如下：
   ```c
   typedef struct Btn {
       TElemType data;
       ;
   } BTN *BT;
   ```
6. 在有n个叶子结点的哈夫曼树中，总结点数是                    。

### 三、综合题（共52分）

1. （共12分）假定关键字输入序列为19，21，47，32，8，23，41，45，40，画出建立二叉平衡树的过程。
2. （共15分）有关键字{13，28，31，15，49，36，22，50，35，18，48，20}，Hash 函数为H=key mod 13，冲突解决策略为链地址法，请构造Hash表（12分），并计算平均查找长度（3分）。ASL=
3. （共10分）设关键字码序列{20，35，40，15，30，25}，给出平衡二叉树的构造过程。
4. （共15分）设哈希表长为m=13，散列函数为H(k)=k mod 11，关键字序列为5，7，16，12，11，21，31，51，17，81；试求：散列后的表中关键字分布（假定解决冲突的方法为线性探测再散列法）；求平均查找长度ASL；计算该表的装填因子。
   - （1）按要求求哈希表（10分）：0 1 2 3 4 5 6 7 8 9 10 11 12
   - （2）计算ASL（3分）： ASL=
   - （3）计算装填因子（2分）：装填因子=

## 使用说明

本资源文件适用于学习数据结构第九章“查找”的学生，提供了详细的作业题目及答案，帮助学生更好地理解和掌握查找算法的相关知识。建议在学习过程中结合教材和课堂讲解，逐步完成作业题目，并通过答案进行自我检查和巩固。

## 贡献

如果您发现任何错误或有改进建议，欢迎提交Issue或Pull Request。感谢您的贡献！

## 下载链接
[数据结构第九章查找作业及答案分享](https://pan.quark.cn/s/ebcc0d9d349f) 

(备用: [备用下载](https://pan.baidu.com/s/11Iw1ATUTE7ANMEZdTQCPLw?pwd=1234))

## 说明

该仓库仅用于学习交流，请勿用于商业用途。
