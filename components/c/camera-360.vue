<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mxzl1tbmo"/><path class="bp7whr02z"/><path class="wy3lou_ac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:camera-360" /></template>
<style>
.bp7whr02z {
  d: path("M5.5 9.5a6.5 2.25 0 1 0 13 0a6.5 2.25 0 1 0-13 0Zm-2.5 6q9 7.5 18 0");
}

.mxzl1tbmo {
  d: path("M5.5 9.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wy3lou_ac {
  d: path("M18.5 15.5H21V18");
}

</style>
