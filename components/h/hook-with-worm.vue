<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bx33w8bcr"/><path class="ac6vhrbbs"/><path class="ysy5x-b_b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hook-with-worm" /></template>
<style>
.ac6vhrbbs {
  d: path("M14 5.75v9.75a4.5 4.5 0 0 1-9 0v-3.75L7.5 14");
}

.bx33w8bcr {
  d: path("M12.25 4a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ysy5x-b_b {
  d: path("M18 7.5q-7.5 1.25-4 3.5t-3.5 3.75");
}

</style>
