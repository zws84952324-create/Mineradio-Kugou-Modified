# Mineradio Modification Notes

This project is a modified version of the original open-source project
`XxHuberrr/Mineradio`. The original project is released under the GPL-3.0
license. This modified version keeps the original license and copyright notices.

## Copyright And License

- The original `LICENSE`, `README.md`, and attribution information should be kept.
- This repository should be published as a modified version based on
  `XxHuberrr/Mineradio`.
- This modification does not include DRM bypassing, paid-feature cracking, or
  copyright circumvention.
- The project is intended for learning, research, UI customization, and feature
  extension.

## Main Changes

1. Added Kugou Music account session support.
   - Added Kugou cookie/session storage.
   - Added Kugou login status, cookie import, and logout routes.
   - Added `/api/kugou/user/playlists` for user playlist synchronization.
   - Added `/api/kugou/playlist/tracks` for playlist track loading.
   - Added `/api/kugou/song/url` for resolving playable song URLs when possible.

2. Added Kugou Music as a third source in the player UI.
   - Added Kugou login tab and account switching entry.
   - Added Kugou playlist group in the playlist panel.
   - Added `KG` source tags for Kugou songs.
   - Added Kugou playlist loading and queue playback support.

3. Improved playlist scrolling style.
   - Added a more transparent, glass-like scrollbar style for the playlist area.

## Important Notes

Kugou Music does not provide a stable public API for all personal music data.
This modification uses the saved login session and compatible web/mobile
endpoints when possible. If Kugou changes its service behavior, some playlists
may fail to load or some songs may not be playable.

Please do not use this project to infringe music platform copyrights or bypass
paid access restrictions.
