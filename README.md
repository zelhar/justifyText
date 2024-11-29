# justifyText
Little Haskell app to justify text

### Installation instruction
To install you must have Haskell Stack installed in your system.
An easy way to install it is with ghcup: https://www.haskell.org/ghcup/ 
Then from this git folder in a terminal window:
`>cd justifyText` (the subfolder of the main git folder with the same name.)
then `>stack install`


### Usage
The program reads from stdin and writes to stdout. It also accepts one integer paramerter for the linewidth (default is 68) 
Example with the text file from the test folder: in a Linux terminal do:

```
# with textwidth parameter
cat sample.txt | justifyText-exe 72

# without params width=68
cat sample.txt | justifyText-exe

# to right aligne instead of justify just add a second parameter of any value
# with textwidth parameter
cat sample.txt | justifyText-exe 48 blabla
```
