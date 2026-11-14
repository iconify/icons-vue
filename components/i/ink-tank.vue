<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u0ceh0t7m"/><path class="dqvg70bvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ink-tank" /></template>
<style>
.dqvg70bvr {
  d: path("m12 12l2 3a2.25 2.25 0 1 1-4 0Z");
}

.u0ceh0t7m {
  d: path("M8 2.5h8v4H8Zm2 4V9H6.5A2.5 2.5 0 0 0 4 11.5V19a2.5 2.5 0 0 0 2.5 2.5h11A2.5 2.5 0 0 0 20 19v-7.5A2.5 2.5 0 0 0 17.5 9H14V6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
