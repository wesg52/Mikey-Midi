# Mikey-Midi
A python tutorial motivated by music.

We start by going through basic python concepts and work towards using music libraries in python for signal processing and working with MIDI data.

## Useful Links
* [Intro to computer science using Python](http://www.greenteapress.com/thinkpython/thinkCSpy.pdf)
* [Examples of music programs written in python and music python packages](https://wiki.python.org/moin/PythonInMusic)
* [Midi Library pretty-midi](http://craffel.github.io/pretty-midi/#)
* [Signal processing library pyo](http://ajaxsoundstudio.com/pyodoc/)


## Getting started
The first piece of software you need is [git](https://git-scm.com/download/win), which is how we will share code. Download and install the 64-bit version. Consider creating a github account as well.

Next we have to get your computing environment set up.

The second piece of softare you need is anaconda which is a python package and environment manager. Follow [this](https://www.datacamp.com/community/tutorials/installing-anaconda-windows) tutorial on how to install it on windows. Note, for step 6 indicate that you DO want to add anaconda to your PATH variable. VSCode is a good IDE (place to type code) so if you don't have one it is worth installing that too.

Now open up an anaconda prompt. Using the cd (change directory) command, navigate to the directory where you want this tutorial to live. Then use git to clone this repository. For instance:
```
cd documents
git clone xyz
```
Your first exercise is to figure out what the xyz should be. (Hint: it is a URL)

Now the code from this repo should be in Mikey-Midi folder. Go to this directory from the command line.

Next we need to install the right python packages (this will take 5+ minutes to finish). I made it easy for you by creating a dependencies file. Run
```
conda env create -f environment.yml
conda activate midi
```
Everytime you close out of this prompt you will need to rerun the second command to activate the `midi` environment. This is to isolate different packages and versions. For instance for your class you might need a different version of python and/or different versions of packages so this is a way to keep everything tidy.

Great, theoretically you have everything you need to get started. Getting your computing environment set up is an exercise in and of itself (I will be amazed if nothing went wrong) so good job getting this far.

## The Tutorial
The tutorial is contained in a series of jupyter notebooks. Notebooks are an excellent way to quickly iterate and save intermediate outputs instead of having to rerun an entire script everytime you want to try something. The notebooks start with basic python concepts that you must familarize yourself with. The emphasis is on python primitives that are the most useful for using the music packages. It is intentially brief, and I encourage you to reference the attatched textbook for a deeper understanding. (This happens to be the textbook that I frantically read the 4 days before my first summer research job to learn python, a language I told the professor I was "already familiar with")

After the basics are out of the way, we can start with the actual MIDI concepts. I am not as musical, so I don't even really know what the right things to teach you are, but hopefully I can get you a decent foundation and you can look up specific things as you need them (learning how to Google what you need is a top 3 most important skill for a programmer).

When you think you finish a notebook, run 
```
git add xyz.ipynb
git commit -m "This is where you type a message about you commit like finished notebook 1"
git push origin master
```
and let me know. I will then push the solutions so you can compare. If you finish before my break is over, I can continue to make up more advanced exercises to show you anything else you might be interested in.




