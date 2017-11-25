# Pre Course Git Fu

## Terms for learning Git
 * Repository - A place where you can store your project. Sometimes abbreviated Repo. It is defined as a central location in which data is stored and managed.
 * Git - Version Control - A tool or system that facilitates the storing of information among multiple users. It is a distributed revision control system that supports distributed non-linear workflows. It is widely used by software developers as a source code management software. 
 * Clone - A clone is a copy of a repository. This command copies an existing repository in the directory you specifiy.
 * Fork - Allows you to copy a repository and change or modify the contents without affecting the original reposiotory. This lets you contribute or propose ideas to the existing project or use the project as a starting point for your own project.
 * History - A group of snapshots that are tipically composed of commits. This lets you ovserve the history of the project in a linear graph. Branch history is also available and acts the same as the commits. Both are stored as snapshots that you can anazlyze. 
 * Staging - Prepares the project to commit. You can stage certain parts of the project for commit and ommit others. This is due to Git's indexing system, which allows the user to Stage different parts of the project.
 * Remote - Acts like a bookmark that lets you pull or push code from a different repository. This repository may be on your local computer or in a different folder or remote server.
 * Commit - Acts as a way to verify the contents that you have added/commited. This command basically records changes to the repository. When you commit, the commits that you have done live in the local repository. When you push, they are sent and transfered to a remote server.
 * Push - Modifies the files and transfers them to a remote server.

## Steps to our Lamba School Git Flow
1. Fork repository
2. `git clone` w/ the repository URL 
3. After Changes Made: `git status`
4. `git add <file-name>` 
5. `git status` to check what is staged
6. `git commit -m 'made changes to the Readme'`
7. `git push`