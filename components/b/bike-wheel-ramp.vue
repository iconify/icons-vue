<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y595pebeh"/><path class="gagpxubwp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bike-wheel-ramp" /></template>
<style>
.gagpxubwp {
  d: path("M5.5 15L9 9.25l4.5-1.75l2 3.75m-2-3.75L12.75 5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y595pebeh {
  d: path("m2.5 19.5l19-7.5m-19 3a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm10-3.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

</style>
