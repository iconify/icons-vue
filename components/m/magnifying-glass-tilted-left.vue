<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="wxczomb9b"/><path class="cmyp6g7zp"/><defs><path id="SVGXRI1fdmo" class="vozdd2sgy"/></defs><use href="#SVGXRI1fdmo" class="dz-kf-l3n"/><clipPath id="SVGqdCmGbAB"><use href="#SVGXRI1fdmo"/></clipPath><path clip-path="url(#SVGqdCmGbAB)" class="bmjanb4ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:magnifying-glass-tilted-left" /></template>
<style>
.bmjanb4ml {
  fill: var(--svg-color--855c52, #855c52);
  d: path("M111.23 125.77c.18-2.04 1.51-4.45 2.37-5.81c2.57-4.07 5.8-7.44 10.62-8.72c4.9-1.31 5.39 2.38 4.22 6.12c-1.41 4.51-4.22 7.9-8.36 10.27c-.97.56-2.26 1.35-3.38 1.52c-2.74.39-5.76.04-5.47-3.38");
}

.cmyp6g7zp {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.44 71.77c-14.16-14.17-14.16-37.15 0-51.31c14.17-14.17 37.12-14.16 51.3 0c14.16 14.16 14.16 37.12 0 51.31c-14.19 14.16-37.14 14.16-51.3 0");
}

.dz-kf-l3n {
  fill: var(--svg-color--f79329, #f79329);
}

.vozdd2sgy {
  d: path("M126.53 110.53L101 84.94c-6.5-6.5-22.18 9.77-15.97 15.97l25.53 25.59c2.64 2.63 8.36 1.19 12.75-3.23c4.41-4.4 5.85-10.11 3.22-12.74");
}

.wxczomb9b {
  fill: var(--svg-color--78a3ad, #78a3ad);
  d: path("M101.53 92.93L82.56 73.98c13.78-18.01 12.49-43.86-3.99-60.34c-17.94-17.93-47.02-17.93-64.97 0c-17.93 17.94-17.93 47.03 0 64.96c16.48 16.47 42.34 17.78 60.35 3.99l18.97 18.96z");
}

</style>
