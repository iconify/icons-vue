<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g6ulkabjn"/><path class="onq-g9bwv"/><path class="g6bc9hbny"/><path class="vfxp4nbje"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:animal-camouflage" /></template>
<style>
.g6bc9hbny {
  d: path("M10.5 9.5c0-2.5 3-3.75 5.25-3s3 3.5 1.75 5.5s-4.5 2-5.75.75c-1-1-1.25-2.25-1.25-3.25Z");
}

.g6ulkabjn {
  d: path("M2.5 2.5h19v19h-19Z");
}

.onq-g9bwv {
  d: path("M5.5 8c0-2.5 2-3.5 4-3.25S12 7 11.25 9S8 11.5 6.75 10.75C5.75 10.25 5.5 9 5.5 8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vfxp4nbje {
  d: path("M6.5 16.5c0-2.25 3-3.75 6-3.25s5.25 1.75 5 3.75c-.25 1.75-3 2.25-5.75 2c-3-.25-5.25-.75-5.25-2.5Z");
}

</style>
