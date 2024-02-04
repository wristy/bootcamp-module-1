# Module 1: Swift Basics


## What you'll accomplish

- [ ] Initialize variables and constants, using implicit and explicit notations.
- [ ] Perform algebraic operations using Swift operators.
- [ ] Perform String operations.
- [ ] Implement conditional statements using logical operators.
- [ ] Referencing optionals.
- [ ] Safely unwrap optionals.


## Requirement

Fork this repo using the instructions outlined below.

For each module, you'll be creating a fork of the module repo which will be
associated with your account.

To fork, click on the "Fork" button on this module's Github page.
It should be located between "Watch" and "Star".

![Image highlighting the Fork button on Github.](module0-img1.png)

In the *Create a new fork* page, you shouldn't need to change anything, but
it should have the following configuration:

- Owner is your github account
- Repository name is identical to forking repo (`bootcamp-module-1`)
- The option to *copy the main branch only* is checked.

![Image showing fork creation screen.](module0-img2.png)

After pressing the *Create fork* button, you should be redirected to your
newly forked repo page.

### Clone a repo with Xcode

1. Open the Xcode app and click `Clone Git Repository`

![Image showing Github clone popup within forked repo.](module0-img4.png)

2. Enter the URL of the git repo. Refer to the image below to locate the URL.
   _Note:_ Make sure to clone the **SSH** url, _not_ the HTTPS url.
   
![Image showing Github clone popup within forked repo.](module0-img3.png)

3. Select the folder you want to store the repo. You'll need this throughout
   the course so don't just put it in your downloads!

4. Xcode should now open up with the cloned repo. Or it'll crash. It's Xcode.

5. If Xcode doesn't open immediately, go to the folder you just cloned and right click on `SwiftBasics.playground`, select Open With -> Xcode.

#### Command line equivalent

```
cd [project destination path]
git clone https://github.com/gtiosclub/bootcamp-module-1.git
```

## Content

### Variables and Data Types

This section of the assignment will serve as a warm-up to help you get comfortable with Swift's variable and type declaration syntax. By the end, you should be able to distinguish between different data types as well as *variables* and *constants*.

- [x] Initialize variables and constants, using implicit and explicit notations.

### Operators

Here, you'll be asked to fulfill certain prompts that require the use of operators. Operators can be used to perform algebraic operations with numbers, or even combine strings. Since you'll be using them a lot during your iOS journey, we suggest getting familiar with them.

- [x] Perform algebraic operations using Swift operators.
- [x] Perform String operations.

### Conditionals

Conditionals let us execute code *conditionally*. They allow us to make decisions in our code when the state of our application isn't clear. All modern languages offer conditional statements, so you may already have experience. This section should push you to learn about the syntax of conditional statements in Swift, and usage of logical operators with conditionals.

- [x] Implement conditional statements using logical operators.

### Optionals

You will find this section much more challenging than the preceding ones. This is because Optionals are a fairly unique feature of Swift, they add a protection layer to **nil** (also known as null in Java, and None in Python). With Optionals, we can write more type-safe code and express values of data types like Strings, Ints, etc. more clearly.

- [x] Referencing optionals.
- [x] Safely unwrap optionals.


## Submission

Make sure you have committed and pushed your local changes to the remote repo, so that we can see your work when we access this link. Refer to module-0 and the Git slides from Day 2 if you are having trouble, or reach out via Discord.

To submit your work, paste the link for the forked repo next to your name under Week 2 &rarr; Assignment of the Student Dashboard (Notion). Make sure you are logged into your Notion account, otherwise you won't have edit permissions.
