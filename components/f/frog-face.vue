<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x7kjbrtkm"/><path class="hnkrrd1os"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:frog-face" /></template>
<style>
.hnkrrd1os {
  d: path("M7 14.5q5 3.5 10 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x7kjbrtkm {
  d: path("M3.5 7.5a3.5 3.5 0 0 1 7 0h3a3.5 3.5 0 0 1 7 0c1 2 1 3.5 1 6C21.5 18 17 20 12 20s-9.5-2-9.5-6.5c0-2.5 0-4 1-6Zm3.5-1h.01m9.99 0h.01");
}

</style>
