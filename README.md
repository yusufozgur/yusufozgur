## Hi there, I am Yusuf 👋

[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=12A76E&lines=Welcome+to+my+profile!)](https://git.io/typing-svg)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![Polars](https://img.shields.io/badge/polars-0075ff?style=for-the-badge&logo=polars&logoColor=white)
![uv](https://img.shields.io/badge/uv-%23DE5FE9.svg?style=for-the-badge&logo=uv&logoColor=white)

What do I do?

- Research how to make biological deep learning models interpretable
- Develop software for analysis of biological data

Everyone has a different approach to coding, and a different sense of beauty. As for me, I believe software should be comprehensible, reproducible, and pragmatic. Software should be a tool, and most importantly, it should never be a burden. In the current world where quality of the code is eroding rapidly by automated systems and human sloth, one should resist and put forth a great product by having their own principles and a strict work ethic. 

Here is a list of my current opinions that frequently come up in conversations. One should be open to change and improvement, so this list may change over time.

- **Python** vs **R**: Python is the second best language for any task, compared to R, python incentivizes better development practices. Especially if you are a researcher, learn and use python as your high-level language.
- **OOP** vs **FP**: You should not confine yourself to one paradigm, you should learn aspects of both and use them according to the situation. Wrapping state and related functions in an object is intuitive and leads to useful patterns, but treating object oriented programming like a dogmatic ritual leads to phenomena like 'Inheritance Hell'. Prefer composition of multiple inheritance. Shy away from mutable global variables, embrace functional transformations and declarative logic.
- **Jupyter** vs **Marimo** Notebooks: I am against jupyter notebooks for most applications. It is a relic of an older era, and should be treated like it. Overreliance on jupyter notebooks scares beginner researchers from properly architecturing their projects, and leads to million line notebooks that are fragile, with many "But it works on my machine" problems. Many usecases for jupyter notebooks can be simply replaced by python scripts, and it would help a lot with reproducibility, as scripts can have a straightforward logic flow, compared to a bunch of jupyter cells all sharing a global state. For usecases where a notebook is needed, be it for interactive usecases or for prototyping, a marimo notebook should be used. Marimo fixes most problems with notebooks, it enforces inter-cell dependencies to be immutable, and it leads to prevention of many logic bugs.
- **Pandas** vs **Polars**: Do not use pandas, polars has a better API, it is also faster and it equips you with better tools to handle larger than memory datasets.
- **Typer**: really useful for building cli apps in python.
- **Pip** and **venv** vs **Uv**: It is astonishing that a competent dependency management tool such as uv was developed this late into the evolution of python. Uv keeps a list of dependencies used by the project in a lockfile, and this allows reliable reproducement of python virtual environments in other machines at later times, and syncronizes dependencies in a reasonable timeframe. Before uv, tools like pip and conda would be used and many hours were lost just attempting to obtain correct dependencies for a project.
- **Conda** vs **Pixi**: Do not use conda, it is a waste of time to learn and use. Pixi is what uv is to pip for conda, and uses uv under the hood for python dependencies.
- **Deep Learning Frameworks**: New learners should learn pytorch, as deep learning research have moved on from tensorflow and other old technologies. JAX is an interesting up and coming alternative.
- Document typesetting: stop using WYSIWYG editors or latex/tex, use typst.
