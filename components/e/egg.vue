<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e5zc08dur"/><path class="wgl-673uv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:egg" /></template>
<style>
.e5zc08dur {
  d: path("M14.5 2.75c4.25 1.25 5 8.25 3.75 13C17 20 13.5 22.25 9.5 21.25c-3.75-1-6-4.75-4.75-9.25C6 7.25 10 1.75 14.5 2.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wgl-673uv {
  d: path("M8 14.5c0-2 .75-4 2-5.5");
}

</style>
