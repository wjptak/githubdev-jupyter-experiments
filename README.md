# Pure GitHub.Dev Python Jupyter Notebooks experiments using [Pyodide](https://github.com/pyodide/pyodide)

The idea of this experimental mini-project is to walk through several possibilities of creating and running a basic Python-based analytics and Data Science stack directly in the browser. The point is to use a local clean browser only without any other cloud-based or local environments. No docker images, VMs, no cloud-based resources will be used. Just your pure browser.

## What I wanted to test 🧐

* Setting up a project in a completely free environment (yes I know, projects like like [Google Colab](https://colab.research.google.com) are also free) (done).
* Running it completely directly in a browser, without use of cloud-based spinned machines (so yes, in contrast to [Google Colab](https://colab.research.google.com)) (done).
* How much can be done and how useful some basic tasks are like getting data, basic data crunching and cleaning using Numpy and Pandas, some visualisations using Matplotlib (or any others) (in progress).
* See if all of that can be done using a reasonably modern tablet or even a phone (in progress).

## What notebooks will you find here 😊

* [Hello World!](./00-basic_browser_tests.ipynb)
* [Jupyter's basic operations](./01-basic_operations.ipynb)
* [Some Numpy tests](./02-numpy_in_the_browser.ipynb)
* [Playing with visualisations using Matplotlib](./03-visualisations_in_the_browser.ipynb)
* [Pandas operations benchmarks](./04-pandas_in_the_browser.ipynb)
* Getting real world data and playing with it (in progress)
* SQLite operations (todo)
* Some basic ML benchmarks (todo)

## Steps to setup your own environment 💻

* Use [Google Chrome](https://www.google.com/chrome/), [Brave Browser](https://brave.com/) or any other [Chromium based browser](https://en.wikipedia.org/wiki/Chromium_(web_browser)#Active) on your laptop or a PC.
* Enable third party cookies, which is required for GitHub.dev to work properly (instructions for [Google Chrome](https://support.cloudhq.net/how-to-enable-3rd-party-cookies-in-google-chrome-browser/) and [Brave Browser](https://support.brave.com/hc/en-us/articles/360050634931-How-Do-I-Manage-Cookies-In-Brave-)).
* Set up your own GitHub account if you haven't got one,
* Use this repo, or fork it, then press "." to enter GitHub.dev Visual Studio Code environment, or replace "github.com" with "github.dev" in browser's web address.
* Once Visual Studio Code online opens, the only thing now is to add an extension for [Pyodide](https://github.com/pyodide/pyodide) - open "Extensions" and install [vscode-pyodide](https://marketplace.visualstudio.com/items?itemName=joyceerhl.vscode-pyodide)
* Make yourself a cup of tea or coffee and have fun!

So far I tested the following:

* Brave Browser on a laptop or a PC - works perfectly fine,
* Safari and Firefox on a laptop - I couldn't make them work (still trying),
* Safari, Chrome and Firefox on an iPad - I couldn't make them work (still trying).

## Why this got me excited? 🥳

If you needed a free quick solution to do a Python-based data analytics project so far, there was only a choice between:

* You need to set up your own fully blown environment (or at least download and setup a Docker or a VM with such environment, assuming you're familiar with all of it).
* Use an environment in the cloud (like [Google Colab](https://colab.research.google.com) or [Kaggle Notebooks](https://www.kaggle.com/docs/notebooks)).

Of course, there are other options, but I stress out "a free quick solution" bit.

While these are perfect scenarios for most projects of that kind, there wasn't an option to have a quick free solution for simple tasks without setting up any accounts (other than GitHub, which I presume you already have). This is a great opportunity that can be used by less technical users.

Furthermore, this project runs directly in the browser, simplifying the stack and enabling you to do some quick experiments, while being fully useful!
