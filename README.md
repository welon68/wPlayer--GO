wPlayer

wPlayer is a lightweight web-based music player for your personal CD collection  
ripped to **FLAC** or **MP3**, packaged as a **single Go binary**.

It is designed for self-hosting on a NAS, home server, or embedded Linux device  
and works as a frontend for **MPD (Music Player Daemon)**.

No Apache. No Docker required. Minimal setup.

---

## Features

- 🎶 Playlist management
- 💿 Album view
- ➕ Add tracks and albums to the queue
- 📊 Playback statistics
- 🌐 Web-based player (HTML / JS)
- 🎨 Clean and responsive interface
- ⚡ Fast startup (single Go binary)
- 🐧 Designed for Linux (ARM / x86)


<img width="1896" height="913" alt="image" src="https://github.com/user-attachments/assets/9f7ad84c-85ea-45ee-a5f9-9c1c048bf2bd" />

How to run. 
./wPlayer

== wPlayer startup check ==
✅ mpd found
✅ mpc found
✅ /music found
✅ MPD responding
============================
Listening on http://0.0.0.0:8080

Your music directory.
/music

The recommended structure is **flat and album-based**:

/music
├── Album 1
│ ├── 01 - Track.flac
│ ├── 02 - Track.flac
│ └── cover.jpg
├── Album 2
│ ├── 01 - Track.mp3
│ └── cover.jpg
└── Album 3
├── 01 - Track.flac
└── cover.jpg

