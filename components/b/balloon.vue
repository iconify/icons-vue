<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ac81cebuy"/><path class="ru268bc2h"/><path class="erwtixpxd"/><path class="u5u5osr6d"/><path class="ryx-kq8vr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:balloon" /></template>
<style>
.ac81cebuy {
  fill: none;
  stroke: var(--svg-color--64b5f6, #64b5f6);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("M75.87 102.1c3 4.9-2.38 10.12 1.85 13.91c7.84 7 17.44-12.05 29.49 7.49");
}

.erwtixpxd {
  fill: var(--svg-color--f44336, #f44336);
  d: path("M25.56 51.54C33.14 83.3 64.22 97.75 75.68 95s32.1-32 25.08-61.43C95.79 12.8 74.93 0 54.16 4.97s-33.57 25.83-28.6 46.6z");
}

.ru268bc2h {
  fill: var(--svg-color--f44336, #f44336);
  d: path("m74.5 106.88l5.63-1a2.86 2.86 0 0 0 2.07-4.1a34.6 34.6 0 0 0-7.2-9.62c-.44 2.89-2.16 7.38-3.62 10.8a2.85 2.85 0 0 0 3.12 3.92");
}

.ryx-kq8vr {
  fill: var(--svg-color--ff847a, #ff847a);
  d: path("M78.28 13.44c-4.07-2.48-9.9-4.13-13.2.55c-1.76 2.49-.1 7.15 3.53 8.2c6.14 1.79 7.21 4 8.46 5.79c1.51 2.1 2.94 4.73 5.49 5.14s4-1.51 3.89-5.21c-.02-5.92-3.11-11.4-8.17-14.47");
}

.u5u5osr6d {
  fill: var(--svg-color--c62828, #c62828);
  d: path("m73.43 98.11l5.16-1.23c1.63-.39 2.64-2.02 2.25-3.65s-2.02-2.64-3.65-2.25L72 92.21c-1.63.39-2.64 2.02-2.25 3.65s2.02 2.64 3.65 2.25z");
}

</style>
