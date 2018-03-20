# tutorial_IPython
Quck tutorial for setting up development environment for IPython


# What is IPython?
I(teractive)Python is an interactive development environment for Python.
We use IPython in the Jupyter Notebook for easier and interactive development.

Some useful features include:
* A notebook (*.ipynb) contains python code as well as some comments.
* You can launch your notebook from (any) web brower on your local machine while real computing is performed on a remote server.
* You can run block-by-block!This is very useful for debugging.

For more detail information, see the official website: [https://ipython.org](https://ipython.org).

Another good source is this book [Learning Ipython for Interactive Computing and Data Visualization (2nd ed.)](https://www.packtpub.com/big-data-and-business-intelligence/learning-ipython-interactive-computing-and-data-visualization-sec).


# How to install?
The easest way to install Ipython is to use pip as follows.
```
pip install ipython
```


# How to use it?
You have two options to run and edit Ipython notebooks.

### on local machine
1. Open an Terminal
2. Go to the folder with your notebooks
3. Launch the server 
```
ipython notebook
```
4. Open (any) web browser and go to localhost:8888
5. In the web browser, you can run each block by Shift+Enter.

### launch remotely on a server 
The only difference from the local-launch is that you use SSH turnelling. 

See here for detail steps. 
[https://coderwall.com/p/ohk6cg/remote-access-to-ipython-notebooks-via-ssh](https://coderwall.com/p/ohk6cg/remote-access-to-ipython-notebooks-via-ssh)
