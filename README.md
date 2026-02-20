# Tutorial Homework Assignment

Currently, this project only contains a single diagram, named `Class Diagram`, in the package `Model/Structure`. 

Using GitHub actions, every diagram is rendered on a different branch, `renders`, enabling easy documentation creation: by using the fully qualified name of the diagram (e.g., `Model.Structure.Class_Diagram`), the render can be included in Markdown files:

![diagram](../../raw/renders/Model.Structure.Class_Diagram.svg)

Use this method to create your documentations throughout the semester. 

# Tasks (no points)

0. Clone this repository using SmartGit. Refer to the [documentation](https://docs.syntevo.com/SmartGit/Latest/) if you get stuck.
1. Modify the diagram by renaming `Class 2` to something more informative. Save and commit to a new (feature) branch. Push the branch to remote.
2. Open a pull request from the new branch towards main.
3. Look at the checks under the newly opened pull request. Make sure they all pass. **Do not merge the PR yet.**
4. Checkout the main branch again, re-open the model, and rename `Class 2` to another name, **different to that of step 1**. Save and commit to a new (feature) branch. Push the branch to remote.
5. Open a pull request from the new branch towards main. If the checks pass, merge the PR.
6. Look at the first PR again. See if there is a merge issue (there should be).
7. In SmartGit, checkout the branch corresponding to the first PR. Try and merge (or rebase) main into this branch. Recognize there is a merge issue (there should be).
8. Using LemonTree (from within SmartGit), solve the merge issue by choosing one of the modifications (doesn't matter which). Commit and push the results. Merge the PR.

 
Ez egy új sor
