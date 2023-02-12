# Coderino
Desktop client for https://adventofcode.com/

Built using Tauri https://tauri.app/

Work in progress...

Features:
- ...
- ...
- ...

## :lock: Prerequisites
The majority of crates which Tauri uses require a couple of system dependencies.
Run the below commands for all requirements (if you are on Debian GNU/Linux).
```bash
sudo apt-get update
sudo apt-get install libwebkit2gtk-4.0-dev \
    build-essential \
    curl \
    wget \
    libssl-dev \
    libgtk-3-dev \
    libayatana-appindicator3-dev \
    librsvg2-dev
```

Install Rust with the following command
```
curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh
```
and verify the installed compiler version with the command below.

```
rustup update
rustc --version
```
Now your system should be ready to handle compilation of the Tauri desktop app!

## :clipboard: License
All code is to be held under a general MIT license, please see [LICENSE](https://github.com/willeagren/coderino/blob/75cdceeaaea4b1f716e638c1d16b7bd8ab0e59c8/LICENSE) for specific information.
