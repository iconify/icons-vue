<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wyh8whbzr"/><path class="fd0udqqmz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blood-pressure-check" /></template>
<style>
.fd0udqqmz {
  d: path("M9.5 14.5c0 3 2 3.5 5 3.5m0 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm-5-9.5l2.75-2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wyh8whbzr {
  d: path("M3.5 8.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0Z");
}

</style>
