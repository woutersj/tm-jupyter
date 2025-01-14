# Jupyter client for TeXmacs

Version 0.2.0 -- (c) 2021 Massimiliano Gubinelli, Jeroen Wouters

Allows for interactive TeXmacs sessions with Jupyter kernels such as IPython, IJulia, IRKernel, IHaskell,....

In development, many things to fix: rich output, interaction, help...

Based on jupyter_console, a terminal-based console frontend for Jupyter kernels.
jupyter_console is released under a modified BSD license, see COPYING.md

- [Jupyter protocol](https://jupyter-client.readthedocs.io/en/latest/messaging.html#messaging)

## Installation

To install the plugin, clone the repository, rename its directory to `jupyter` and copy it into either the `$TEXMACS_PATH/plugins` or `$TEXMACS_HOME_PATH/plugins`. As stated in the TeXmacs documentation: by default, the path `$TEXMACS_HOME_PATH` equals `%appdata%\TeXmacs` on Windows or `$HOME/.TeXmacs` on GNU/Linux and macOS.

The list of installed Jupyter kernels will appear under Insert → Session → Jupyter.

## Additional resources
- [Project Jupyter website](https://jupyter.org)
- [Documentation for Jupyter Console](https://jupyter-console.readthedocs.io/en/latest/) [[PDF](https://media.readthedocs.org/pdf/jupyter-console/latest/jupyter-notebook.pdf)]
- [Documentation for Project Jupyter](https://jupyter.readthedocs.io/en/latest/index.html) [[PDF](https://media.readthedocs.org/pdf/jupyter/latest/jupyter.pdf)]
- [Issues](https://github.com/jupyter/jupyter_console/issues)
- [Technical support - Jupyter Google Group](https://groups.google.com/forum/#!forum/jupyter)
