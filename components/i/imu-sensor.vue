<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fgjqqccuv"/><path class="xbubrifgu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:imu-sensor" /></template>
<style>
.fgjqqccuv {
  d: path("M5.75 18.25a8.75 8.75 0 1 1 12.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xbubrifgu {
  d: path("M18.25 15.75v2.5h2.5M8.5 8.5h7v7h-7Zm2 0V7.25m3 1.25V7.25m-3 8.25v1.25m3-1.25v1.25m-5-6.25H7.25m1.25 3H7.25m8.25-3h1.25m-1.25 3h1.25");
}

</style>
