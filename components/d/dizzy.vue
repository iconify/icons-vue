<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><linearGradient id="SVGhSdPIdMn" x1="93.73" x2="52.9" y1="21.25" y2="46.2" gradientTransform="matrix(1 0 0 -1 0 127.89)" gradientUnits="userSpaceOnUse"><stop offset=".1" class="sc9knx3mp"/><stop offset="1" class="o2cb85fyr"/></linearGradient><linearGradient id="SVG3JUgTdWd" x1="115.28" x2="14.86" y1="45.53" y2="127.07" gradientTransform="matrix(1 0 0 -1 0 127.89)" gradientUnits="userSpaceOnUse"><stop offset="0" class="sc9knx3mp"/><stop offset=".71" class="y589grvmz"/><stop offset=".84" class="iqw9twb8u"/><stop offset=".98" class="wgh3rtbml"/><stop offset="1" class="o0_-kj7bz"/></linearGradient></defs><path fill="url(#SVGhSdPIdMn)" class="iopzdv8eo"/><path fill="url(#SVG3JUgTdWd)" class="w7sx3mhmy"/><path class="rzg0npb8w"/><path class="vqmbjkbnp"/><path class="uet66pb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:dizzy" /></template>
<style>
.iopzdv8eo {
  d: path("M123.04 107.67c-4.08-4.12-9.38-9.48-14.92-15.06c-.34 1.29-.93 2.39-1.79 3.26c-6.43 6.43-25.6-1.99-45.31-19.1c-2.46-2.13-16.74 20.28-14.1 22.87c3.27 3.2 26 17.86 33.78 20.73c22.66 8.35 34.3.22 38.24-3.59c2.22-2.17 3.57-5.28 4.1-9.11");
}

.iqw9twb8u {
  stop-color: var(--svg-color--fddc36, #fddc36);
}

.o0_-kj7bz {
  stop-color: var(--svg-color--ffeb3b, #ffeb3b);
}

.o2cb85fyr {
  stop-color: var(--svg-color--ffb300, #ffb300);
  stop-opacity: 0;
}

.rzg0npb8w {
  fill: var(--svg-color--fdd835, #fdd835);
  d: path("m55.98 42.1l-.75 20c-.06 1.53.72 2.98 2.04 3.77l16.86 10.11c1.85 1.25 1.46 4.09-.66 4.79L54.79 85.5a4.22 4.22 0 0 0-3.06 3.08l-4.89 19.93c-.62 2.15-3.43 2.65-4.76.85L31.06 92.91a4.22 4.22 0 0 0-3.83-1.85L7.49 92.61c-2.23.07-3.58-2.45-2.28-4.27l12.6-16.19c.96-1.23 1.16-2.89.52-4.31l-7.88-17.57c-.76-2.1 1.22-4.17 3.35-3.49l18.39 6.95c1.44.54 3.05.26 4.22-.74l15.22-13c1.76-1.37 4.33-.12 4.35 2.11");
}

.sc9knx3mp {
  stop-color: var(--svg-color--ffb300, #ffb300);
}

.uet66pb8k {
  fill: var(--svg-color--f4b400, #f4b400);
  d: path("m53.89 83.73l14.53-3.13c.73-.18 2.01-.42 1.64-1.58c-.29-.91-2.34-.8-2.34-.8l-10.97-.86c-3.21-.38-5.72.14-6.74 1.84c-1.36 2.28-.12 5.12 3.88 4.53");
}

.vqmbjkbnp {
  fill: var(--svg-color--ffff8d, #ffff8d);
  d: path("m46.99 59.33l4.66-12.75c.28-.7.7-1.93 1.79-1.4c.86.42.46 2.43.46 2.43l-1.05 11.54c-.41 4.39-1.6 5.38-3.3 5.49c-1.95.11-3.9-1.66-2.56-5.31");
}

.w7sx3mhmy {
  d: path("M25.05 27.7c-1.54-4.81-2.88-11.1-.4-13.5c7.51-7.3 31.69 4.88 54.25 27.43c22.55 22.55 34.84 46.84 27.43 54.25c-.07.07-.16.13-.23.2c6.13 5.82 12.2 11.6 16.1 15.31c4.87-14.43-6.45-44.11-31.5-69.96c-4.07-4.2-16.12-16.56-26.55-23.56c-9.54-6.4-19.96-12.28-31.58-13.67C25 3.29 11.45 5.24 14.25 15.98c.55 2.12 2.31 7.22 8.15 13.3c1.16 1.21 3.16.02 2.65-1.58");
}

.wgh3rtbml {
  stop-color: var(--svg-color--ffe93a, #ffe93a);
}

.y589grvmz {
  stop-color: var(--svg-color--fdd835, #fdd835);
}

</style>
