# bash--Scripting

Bash (or shell) scripting is a great way to automate repetitive tasks and can save you a ton of time as a developer. Bash scripts execute within a Bash shell interpreter terminal. Any command you can run in your terminal can be run in a Bash script. When you have a command or set of commands that you will be using frequently, consider writing a Bash script to perform it.

There are some conventions to follow to ensure that your computer is able to find and execute your Bash scripts. The beginning of your script file should start with #!/bin/bash on its own line. This tells the computer which type of interpreter to use for the script. When saving the script file, it is good practice to place commonly used scripts in the ~/bin/ directory.


Take a minute to review what you’ve learned about bash scripting.

Any command that can be run in the terminal can be run in a bash script.
Variables are assigned using an equals sign with no space (greeting="hello").
Variables are accessed using a dollar sign (echo $greeting).
Conditionals use if, then, else, fi syntax.
Three types of loops can be used: for, while, and until.
Bash scripts use a unique set of comparison operators:
Equal: -eq
Not equal: -ne
Less than or equal: -le
Less than: -lt
Greater than or equal: -ge
Greater than: -gt
Is null: -z
Input arguments can be passed to a bash script after the script name, separated by spaces (myScript.sh “hello” “how are you”).
Input can be requested from the script user with the read keyword.
Aliases can be created in the .bashrc or .bash_profile using the alias keyword.
