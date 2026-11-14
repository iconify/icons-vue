<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wrcg6qhaf"/><path class="sx-_lo3_f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:aquarium-fish-tank" /></template>
<style>
.sx-_lo3_f {
  d: path("M2.5 8.5q2.375-1.5 4.75 0t4.75 0t4.75 0t4.75 0M8 14.5c1.5-2.5 5-2.5 6.5 0l2.5-2v4l-2.5-2C13 17 9.5 17 8 14.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wrcg6qhaf {
  d: path("M2.5 4.5h19v15h-19Z");
}

</style>
