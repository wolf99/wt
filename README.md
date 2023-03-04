# My Home Microsoft Windows Terminal Configuration

## Windows 11 :one::one:

## Requirements

- Windows Terminal
  - If not already available (see [win-config][]) this can be installed with `winget install "Windows Terminal" --source msstore` or from the MS Store GUI
  
## Instructions

1. Clone this repository directory wherever you like
2. Download and install the latest release of the [Caskaydia Cove Nerd Fonts][]
3. Copy the contents of `settings.json` to your Windows Terminal settings and save

## Windows 10 :keycap_ten:

## Requirements

- Windows Terminal v1.0
  - Windows Terminal currently requires Windows OS >= 1903 (build >= 10.0.18362.0)

## Instructions

1. Clone directory into `%HOMEDRIVE%%HOMEPATH%\wt`
    (where %HOMEDRIVE%%HOMEPATH% usually is `C:\Users\{username}\`).
    This means that the icon images will be at the correct location for the
    values used on the settings.
2. Install the font file using the system Font Settings
3. Copy `settings.json` to Windows Terminal settings and save.

[win-config]: https://github.com/wolf99/win-config
[Caskaydia Cove Nerd Fonts]: https://github.com/ryanoasis/nerd-fonts/releases/latest/download/CascadiaCode.zip
