<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rur0mzb4g"/><path class="an9xw6bos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:forward-30" /></template>
<style>
.an9xw6bos {
  d: path("m9 2.5l3 3l-3 3m-1.5 2h3l-1.5 2m0 0c1.25 0 1.75.75 1.75 1.5c0 1-.75 1.5-1.5 1.5q-1.125 0-1.5-.75m5.5-4.25h3v5h-3Z");
}

.rur0mzb4g {
  d: path("M18.495 9.25A7.5 7.5 0 1 1 12 5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
