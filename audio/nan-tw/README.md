# nan-tw fallback audio pack

This folder documents the Hokkien fallback audio source.

Actual runtime audio payload is bundled in `../nan-tw-data.js` as base64-encoded WAV data
(`window.NAN_TW_AUDIO_DATA`) so the page can play Hokkien fallback audio without extra fetch requests.
