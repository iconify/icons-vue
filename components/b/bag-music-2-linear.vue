<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lurpk9itd"/><circle class="vf7wzobiw"/><path class="ye5v0kb6s"/><path class="zr846pb6r"/><path class="hkf_44bqq"/><path class="zr846pb6r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-music-2-linear" /></template>
<style>
.hkf_44bqq {
  d: path("M9 6.01973V5C9 3.34315 10.3431 2 12 2C13.6569 2 15 3.34315 15 5V6.01973");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lurpk9itd {
  d: path("M13 16V13V10");
}

.vf7wzobiw {
  cx: 11px;
  cy: 16px;
  r: 2px;
}

.ye5v0kb6s {
  d: path("M15 12C13.8954 12 13 11.1046 13 10");
}

.zr846pb6r {
  d: path("M11.1481 21H12.851C16.7834 21 18.7496 21 19.9152 19.8616C20.1262 19.6555 20.3138 19.4267 20.4745 19.1793C21.3622 17.8131 20.9766 15.8851 20.2054 12.0291C19.6682 9.34329 19.3996 8.00036 18.5122 7.13543C18.3482 6.97557 18.1707 6.8301 17.9818 6.70061C16.9596 6 15.5901 6 12.851 6H11.1481C8.40907 6 7.03956 6 6.01737 6.70061C5.82845 6.8301 5.651 6.97557 5.48697 7.13543C4.5995 8.00036 4.33092 9.34329 3.79375 12.0291C3.02255 15.8851 2.63695 17.8131 3.52461 19.1793C3.68534 19.4267 3.87293 19.6555 4.08398 19.8616C5.24955 21 7.21574 21 11.1481 21Z");
}

</style>
