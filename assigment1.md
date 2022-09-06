## Task/Assigment 1:
Git Basics Assignment - Your Instructions

1. Create a new folder and initialize the repository
2. Paste the "instructions.txt" file into this folder
3. Add a .txt file named "file-1" containing any text of your choice to the working directory
4. Create a second .txt file named "file-2"
5. Add "file-1" and "file-2" to the staging area - don't add "instructions.txt"
6. Change the initial text you added to "file-1"
7. Now add all working directory files to the staging area
8. Create the first commit
9. Create a second branch named "feature" (two commands are possible)
10. Add a third .txt file ("file-3.txt") to this branch
11. Create a new commit
12. Add the following text to "file-3": "I will be deleted"
13. Add the updated file to the staging area
14. Undo the staged change
15. Add the following text: "Please add me to the master/main branch"
16. Commit this latest change
17. Merge the "master" (or "main") branch with "feature"
18. Delete the "feature" branch


## Answer :
1. mkdir demo
cd demo
git init

2. cp /d/instructions/instructions.txt /d/demo

3.  echo "This is file-1 text" >> file-1.txt

4. echo "This is file-2 text" >> file-2.txt

5. git add file-1.txt file-2.txt

6. echo "Change in file-1" >> file-1.txt

7. git add.

8. git commit -m "First Commit"

9. git checkout -b feature

10. echo "This is third file >> file2.txt

11. git add .

git commit -m "First commit in feature branch"

12. echo "I will be deleted" >> file3.txt

13. git add .

14. git reset file3.txt

15. echo "Pls add me to the master branch" >> file3.txt

16. git commit -m "Latest change"

17. git checkout master

git merge feature

18. git branch -D feature
