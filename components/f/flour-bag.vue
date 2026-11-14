<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bn0nrwk8w"/><path class="zoer28bhv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flour-bag" /></template>
<style>
.bn0nrwk8w {
  d: path("M6.5 7L7 3l2.5 1.25L12 3l2.5 1.25L17 3l.5 4c1.5 3 2 6.5 2 9.5c0 3.25-1.5 5-4 5h-7c-2.5 0-4-1.75-4-5c0-3 .5-6.5 2-9.5Zm0 0h11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zoer28bhv {
  d: path("M10.25 12.5a1.75 3.25 0 1 0 3.5 0a1.75 3.25 0 1 0-3.5 0ZM12 15.75v3.5m0 0q-3-.25-3.25-2.5m3.25 2.5q3-.25 3.25-2.5");
}

</style>
