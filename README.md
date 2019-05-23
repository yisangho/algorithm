## Algorithm

```java
static void main(String[] args) {
  System.out.println("Hello Java");
}
```


You can make a link below.

[Blog Address](https://blog.naver.com/ring717)


> 'Study of Algorithm'

Also you can make a none ordered list below.

* Git Tutorial
  * Git Clone
  * Git Pull
  * Git Commit
    * Git branch
    * Git checkout


You can make a table 

date|job|description
---|---|---|
May 10 2019 | coding | java
May 20 2019 | design | database


Bold

**Study** Algorithm ~~Java~~ world!!


* Make a zip file from branch 
  * When you make a zip file with branch to the same directory
    * git archive --format=zip master -o Master.zip
  * You want to make a zip file from branch to other directory
    * git archive --format=zip master -o ../Master.zip


* Git **rebase** Command
  * This is command for edit or delete of specific commit
  * when you want to edit for commit message with interactive mode 
    * git rebase -i
  * when you want to see the log recent three row
    * git rebase -i HEAD~3
  * when you want to see from specific spot base on hashcode
    * git rebase -i e34c3cb2b98026c0d7e93a60e4648b94c117087f
  * when you want to delete own specific history
    * First, you open the list of log 
             git rebase -i 
      Next, input the rebase command for drop of log
             current > pick 223jkj234 Drop Example1.txt
             update >  drop 223jkj234 Drop Example1.txt
                       This
                       
                       
             
             
