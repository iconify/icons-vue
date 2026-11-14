<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jh--vwb6r"/><path class="iz-2vqt_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:brightness-adjust" /></template>
<style>
.iz-2vqt_x {
  d: path("M12 10a2 2 0 0 1 0 4Zm0-7.5v1.75m0 15.5v1.75M2.5 12h1.75m15.5 0h1.75M5.25 5.25L6.5 6.5m11 11l1.25 1.25m0-13.5L17.5 6.5M5.25 18.75L6.5 17.5");
}

.jh--vwb6r {
  d: path("M7 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
