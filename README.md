# dotfiles

```
apt-get update; apt-get install -y software-properties-common curl;
add-apt-repository ppa:jonathonf/vim -y; curl -s https://deb.nodesource.com/setup_16.x | bash;

apt-get update; apt-get install -y nodejs unzip zip wget zsh vim tmux curl git htop libgl1 libglib2.0-0 rsync; pip install gpustat opencv-python matplotlib einops scikit-image scikit-learn jupyter jupyterlab ipdb easydict seaborn tensorboard pytorch_lightning;
git clone https://github.com/SeongwoongCho/dotfiles.git ~/.dotfiles; bash ~/.dotfiles/install.sh; git clone https://github.com/github/copilot.vim.git ~/.vim/pack/github/start/copilot.vim

```
terminal info: <br>
 - type: xterm <br>
 - colorscheme: New Black <br>
 - font: DejaVu Sans Mono (size: 10)
 - asian font: DejaVu Sans Mono (size: 10)
 - font quality: Natural ClearType
 - bold: Use bold color and font


vim shortcuts
- F2 : turn off search highlight
- F3 : turn on search highlight based on keyword at current cursor position
- F4 : trailing whitespaces from all lines
- F5 : turn on PEP8 checker
- F6 : turn off PEP8 checker
- F8 : paste toggle (on/off)
- F9 : toggle line number (useful when copying a block of lines without line numbers)
