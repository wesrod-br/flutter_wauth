# WAuth - MFA for Cyborgs

This is a simple Android app created for cyborgs - people who have NFC microchips implanted on their bodies.

Using this app, one will be able to generate one-time passwords for most online services, like Google, Twitter, Facebook, Amazon, and many others which allows enabling a virtual MFA app.

## Setup

As pre-requisites, install and configure OpenJDK, Android SDK, 
Android Studio, Flutter and AVDs.

In my setup, using Ubuntu 20.04, I have:

- Installed OpenJDK 8 via APT;
- Installed flutter via git clone;
- Installed Android Studio via Flatpak;
- Installed Android Sdk in ~/Android via Android Studio;
- Configured flutter doctor android-studio-dir to the Flatpak dir;
- Configured all necessary env vars (~/.zsh_facilities/04_configs.sh);

You may want to setup the FLutter SDK folder in VSCode, also.

1. Clone and access the repository:

```bash
git clone git@github.com:wesrod-br/flutter_wauth.git
cd flutter_wauth
```

1. Get the packages:

```bash
flutter pub get
```

1. Run, darling, run! Open the file `lib/main.dart` and click the `run` button.
