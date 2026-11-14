<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w6avi7bwg"/><path class="gn250xbhn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:employee-learning-path" /></template>
<style>
.gn250xbhn {
  d: path("M18 21.5c-1.75-1.75-3-3.25-3-4.75a3 3 0 0 1 6 0c0 1.5-1.25 3-3 4.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w6avi7bwg {
  d: path("M21.5 12.153V4.5C17 4 14 4.5 12 6c-2-1.5-5-2-9.5-1.5v14C7 18 10 18.5 12 20a7 7 0 0 1 .887-.564M12 6v14");
}

</style>
