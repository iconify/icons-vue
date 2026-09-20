<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGQeXDpeaN" cx="64" cy="-1822" r="56.96" fx="64" fy="-1822" gradientTransform="matrix(1 0 0 -1 0 -1758)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGQeXDpeaN)" class="uuo0vn6ns"/><path class="ba4-6rbxq"/></g><path class="exkymlbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:face-with-crossed-out-eyes" /></template>
<style>
.ba4-6rbxq {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37-7.35-48.18-22.94c10.76 17.66 31 25.94 50.18 25.94c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
}

.exkymlbdq {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M82.56 93.95c0 7.58-8.31 12-18.56 12s-18.56-4.45-18.56-12S53.75 78.1 64 78.1s18.56 8.27 18.56 15.85M44.75 57.7l8.46-7.87c1.2-1.49 1.38-3.5.17-4.7c-1.59-1.6-4.41-1.21-5.94.61c-.08.15-.14.19-.22.34l-6 8.72l-8.12-7.57c-.12-.13-.19-.15-.3-.28c-1.89-1.44-4.73-1.2-5.92.71c-.93 1.44-.31 3.35 1.19 4.55l10.41 6.17l-8.82 8.25c-1.18 1.47-1.4 3.47-.18 4.7c1.58 1.61 4.4 1.24 5.94-.57c.08-.15.14-.19.23-.34l6.32-9.14l7.68 7.24c.12.13.19.16.3.29c1.88 1.45 4.72 1.23 5.93-.67c.93-1.44.32-3.36-1.17-4.56zm38.48 0l-8.46-7.87c-1.2-1.49-1.38-3.5-.16-4.7c1.59-1.6 4.4-1.21 5.93.61c.08.15.15.19.23.34l6 8.72l8.13-7.57c.11-.13.18-.15.29-.28c1.9-1.44 4.73-1.2 5.93.71c.92 1.44.3 3.35-1.2 4.55l-10.44 6.17l8.82 8.25c1.21 1.49 1.41 3.49.19 4.7c-1.57 1.61-4.39 1.24-5.93-.57c-.09-.15-.15-.19-.23-.34l-6.32-9.14l-7.69 7.24c-.11.13-.18.16-.3.29c-1.88 1.45-4.71 1.23-5.92-.67c-.94-1.44-.33-3.36 1.16-4.56zM45.65 30c2.3.2 3.2-2.9.8-3.6c-1.89-.51-3.85-.71-5.8-.6c-5.29.2-10.3 2.42-14 6.2c-1.7 1.8.7 4 2.5 2.7a26.23 26.23 0 0 1 16.5-4.7m36.6 0c5.9-.34 11.75 1.31 16.6 4.7c1.8 1.3 4.2-.9 2.5-2.7a20.9 20.9 0 0 0-14-6.2c-1.95-.11-3.91.09-5.8.6c-.98.28-1.55 1.29-1.27 2.27c.24.87 1.08 1.43 1.97 1.33");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.uuo0vn6ns {
  d: path("M64 119.9c-27.9 0-58-17.5-58-55.9S36.1 8.1 64 8.1c15.5 0 29.8 5.1 40.4 14.4C115.9 32.7 122 47.1 122 64s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

</style>
