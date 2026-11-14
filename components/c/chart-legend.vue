<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="isrgbactk"/><path class="myp7s5anr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-legend" /></template>
<style>
.isrgbactk {
  d: path("M2.5 12a6 6 0 1 0 12 0a6 6 0 1 0-12 0Z");
}

.myp7s5anr {
  d: path("M8.5 6v6l5 3.25m4-7.25h3m-3 4h3m-3 4h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
