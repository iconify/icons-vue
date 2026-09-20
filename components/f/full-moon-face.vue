<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<radialGradient id="SVGd6laKefl" cx="63.55" cy="56.074" r="68.672" gradientUnits="userSpaceOnUse"><stop offset=".299" class="bha333bzu"/><stop offset=".4" class="cxj7ffnsn"/><stop offset=".568" class="cj14hs6fk"/><stop offset=".782" class="m1-os0brx"/><stop offset=".843" class="sfaelm-5x"/><stop offset="1" class="zo__s054a"/></radialGradient><circle fill="url(#SVGd6laKefl)" class="wa-xljbbr"/><path class="rsklx3buw"/><path class="p930rbber"/><path class="kqanztb8t"/><path class="j0fc90bpp"/><radialGradient id="SVG6SLO1b7i" cx="87.765" cy="63.367" r="16.37" gradientTransform="matrix(.9201 -.3918 .3131 .7354 -12.827 51.15)" gradientUnits="userSpaceOnUse"><stop offset="0" class="zo__s054a"/><stop offset="1" class="gxyggacbm"/></radialGradient><path fill="url(#SVG6SLO1b7i)" class="bilxpcb7r"/><radialGradient id="SVGmQbkWbCA" cx="-2353.02" cy="63.65" r="16.135" gradientTransform="matrix(-.9201 -.3918 -.3131 .7354 -2108.655 -905.011)" gradientUnits="userSpaceOnUse"><stop offset="0" class="zo__s054a"/><stop offset="1" class="gxyggacbm"/></radialGradient><path fill="url(#SVGmQbkWbCA)" class="c5870ebpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:full-moon-face" /></template>
<style>
.bha333bzu {
  stop-color: var(--svg-color--fff7b3, #fff7b3);
}

.bilxpcb7r {
  d: path("M78.44 73.44c1.55 3.75 7.63 4.79 13.58 2.32c5.95-2.46 9.52-7.5 7.97-11.24c-1.55-3.75-7.63-4.79-13.58-2.32c-5.95 2.46-9.52 7.5-7.97 11.24");
}

.c5870ebpw {
  d: path("M45.3 73.44c-1.55 3.75-7.63 4.79-13.58 2.32c-5.95-2.46-9.52-7.5-7.97-11.24c1.55-3.75 7.63-4.79 13.58-2.32c5.95 2.46 9.52 7.5 7.97 11.24");
}

.cj14hs6fk {
  stop-color: var(--svg-color--fff08f, #fff08f);
}

.cxj7ffnsn {
  stop-color: var(--svg-color--fff5a9, #fff5a9);
}

.gxyggacbm {
  stop-color: var(--svg-color--fbc02d, #fbc02d);
  stop-opacity: 0;
}

.j0fc90bpp {
  fill: var(--svg-color--ffcb38, #ffcb38);
  d: path("M61.8 93.24c-.72.21-1.57.75-1.39 1.48c.06.24.22.43.4.6c.57.52 1.31.82 2.05 1.01c2.09.53 4.35.15 6.25-.85c1.94-1.02 4.57-3.19 3.8-4.83c-.62-1.33-3.01.52-3.94.91c-2.31.97-4.77.99-7.17 1.68");
}

.kqanztb8t {
  fill: var(--svg-color--5d4037, #5d4037);
  d: path("m80.04 77.94l-.12-.07c-.6-.36-1.39-.29-1.92.16c-1.57 1.34-8.08 3.82-14.01 3.94c-5.93-.12-12.44-2.6-14.01-3.94c-.53-.45-1.31-.53-1.92-.16l-.12.07c-.76.46-.9 1.4-.37 2.08c2.06 2.58 7.52 6.46 16.41 6.59c8.89-.12 14.34-4.01 16.41-6.59c.56-.68.41-1.62-.35-2.08");
}

.m1-os0brx {
  stop-color: var(--svg-color--ffe865, #ffe865);
}

.p930rbber {
  fill: var(--svg-color--e2b013, #e2b013);
  d: path("M58.4 72.22c-1.44-1.62-.11-2.46 1.47-1.98c2 .61 5.2.32 6.02-1.48c1.58-3.46-.39-5.41-2.84-11.39c-2.56-6.25.65-13.06 4.35-13.41c2.97-.28 1.98 1.27 1.05 1.93c-1.82 1.3-3.73 5.6-.8 10.42c4.99 8.19 5.4 12.12 2.42 15.98c-1.85 2.4-7.61 4.49-11.67-.07");
}

.rsklx3buw {
  fill: var(--svg-color--5d4037, #5d4037);
  d: path("M42.51 59.81c-1.53 1.25-4.18 1.39-6.42.44c-2.66-1.14-3.87-2.9-3.91-5.65c-.04-3.41 2.8-7.05 8.42-7.41c9.26-.59 12.82 7.71 12.92 8.02c.22.65-.1 1.58-1.95.12c-5.63-4.45-7.65-3.71-7.65-3.71s3.24 4.37-1.41 8.19m42.23 0c-1.53 1.25-4.18 1.39-6.42.44c-2.66-1.14-3.87-2.9-3.91-5.65c-.04-3.41 2.8-7.05 8.42-7.41c9.26-.59 12.82 7.71 12.92 8.02c.22.65-.1 1.58-1.95.12c-5.63-4.45-7.65-3.71-7.65-3.71s3.24 4.37-1.41 8.19");
}

.sfaelm-5x {
  stop-color: var(--svg-color--ffe558, #ffe558);
}

.wa-xljbbr {
  cx: 64px;
  cy: 64px;
  r: 60px;
}

.zo__s054a {
  stop-color: var(--svg-color--fbc02d, #fbc02d);
}

</style>
