# Health Insurance Exploratory Data Analysis Project

This repository is meant to provide some tips and tricks for the Health Insurance Exploratory Data Analysis Project that is part of the AY20 Data Scientist PDSI program.  As part of this repository you will find several files that will help you access the data files stored on the Data Science Playground (DSP) as well as guide you in managing your work.

### The most import message! 
Please remember that there is no private file persistence on the DSP and therefore you are responsible for having a plan to store your files somewhere.  We recommend that you get familiar with GitHub and choose to use the JupyterHub's built-in GitHub extension (or even the command line in the Terminal) to push and pull your scripts and notebooks.  Is it possible to download and upload your files from JupyterHub but the extra effort to learn how to use git will pay off in the end.  Whatever scheme you decide to use for saving your work... save your work often.  You never know when the WREN will go down.

### Why the DSP?
This whole "no private file persistence" thing sounds like a pain... why would I use the DSP at all?  We're pushing you to utilizing this resource because you're going to be dealing with 13.5 GB of data in this project.  Not only is that a lot for everyone to be saving to your local machine but it's a lot for you to be loading into memory on your laptop.  Utilizing this remote resource also helps you get familiar with the perculiarities of working with remote computing.  Ultimately if you decide to download the data and work on your laptop, that's up to you but the server is available for you.

### Data file location
On the DSP homepage (www.wpcdas.com) there is a link called "DataTree".  This link will take you a tree layout of the data directory on the DSP.  You can find the files associated with this project under the "PDSI" directory.  The purpose of this tree is to provide you with a visual representation of the file paths so you can reference the data files when you need to work with them. As an example, the full path to the file "Network.csv" is "/data/PDSI/Network.csv".  If you have chosen to work on these files on your personal computer, you can also download them by clicking their names in the tree.

### Where to work
The DSP has three different JupyterLab kernels available for you: Python 3, R, and Julia.  You can use the notebook interface in any of these languages by choosing the "Normal Environment" when launching your server after logging into JupyterHub.  If you wish to program in R using RStudio, you can also launch this from the "Normal Environment" once you've launched your server.  All of these tools will store your work in a temporary home directory that will disappear once you shutdown your server (or the WREN shuts it down for you).  You should really be on top of saving your work and/or pushing it to GitHub if you hope to not lose anything.  You can see the libraries that come installed in the "Normal Environment" here: https://wp-cdas.github.io/

### Packaging your work
The DSP is built around encouraging reproducible data science, to this end a lot of work has gone into incorporating Repo2Docker functionality that will allow you to compose a recipe for your analysis environment.  You can get more details about this tool in the CDAS Repo2Docker repository here: https://github.com/wp-cdas/Repo2Docker-Python. As of now, Repo2Docker only supports Python environments.  Once you've composed your Repo2Docker repo, you can launch it by selecting the "Repo2Docker" environment and pasting your repository URL in the appropriate textbox.

If you have some other idea for how you'd like to work on this project (environments, tools, etc) please get into contact with Bryan Jonas.

### Source of data
The data we will be using for this project comes from here: https://www.kaggle.com/hhs/health-insurance-marketplace
