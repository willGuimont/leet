# leet
L3371fy y0ur m3554635

Works on Linux, Windows and MacOS.

# Installation

1. Install `xclip`
2. `mkdir ~/bin`
3. Copy leet into `~/bin`
4. `chmod +x ~/bin/leet`
5. Add `PATH=$PATH:$HOME/bin` at the end of your `~/.bashrc`
6. Use with `leet "Elite Hacker"`

# Usage
`leet "Elite Hacker" -x -q`

`echo "Elite Hacker" | mock`

## Interactive mode
`leet` then type sentences to mock.

# Parameters
`leet --help`
```
usage: leet [-h] [-x] [-q] [message]

L3371fy y0ur m3554635

positional arguments:
  message      message to leetify, alternatively you can pipe text into leet

optional arguments:
  -h, --help   show this help message and exit
  -x, --copy   copy leet message to clipboard, only works with last piped line
  -q, --quiet  does not print to terminal
```

