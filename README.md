# cycle-screensaver

An incredibly stupid BASH script I wrote in an evening to cycle through (at the time of writing) `cmatrix`, `htop`, and `sl`. 

## Usage

Install dependencies  
[cmatrix](https://github.com/abishekvashok/cmatrix)  
[htop](https://github.com/hishamhm/htop)  
[sl](https://github.com/mtoyoda/sl)

Clone the repo
```
git clone https://github.com/NaCl10/cycle-screensaver
```

Run it!
```
cd cycle-screensaver
./cycle-screensaver
```

From there, you may move it to a folder that's somewhere on $PATH if you like. `~/.local/bin/` works well if you don't already have somewhere else you put scripts. You can also stick it in a system directory like `/usr/bin/` if you want all users to be able to access it.

## Contributing

Open a pull request! I'm happy to accept any useful contributions. That's what open-source is for!

If you can think of another screensaver-like program that should be implemented, fork it, implement it, and open a PR. I'd love to add some more programs, I just can't think of any off the top of my head. (See below for some notes on asciiquarium)

## Why isn't asciiquarium in here?

It's an absolute BITCH and refuses to do things like die when sent any sort of kill signal, properly clear itself, etc. (I'm pretty sure I summoned a terminal-based deamon several times while attempting to implement it) If you can get it working, open an issue or a PR. I'll be happy to implement it.
