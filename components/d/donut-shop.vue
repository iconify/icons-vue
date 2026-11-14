<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e0dvv9mob"/><path class="dib99cfsp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:donut-shop" /></template>
<style>
.dib99cfsp {
  d: path("M8.5 11a3.5 1.75 0 1 0 7 0a3.5 1.75 0 1 0-7 0ZM3 13.5q2 3.5 4.5 2q2.5 2 4.5.5q2 1.5 4.5-.5q2.5 1.5 4.5-2");
}

.e0dvv9mob {
  d: path("M2.5 13a9.5 7 0 1 0 19 0a9.5 7 0 1 0-19 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
