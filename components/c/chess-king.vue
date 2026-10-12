<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n0vqr9bmc"/><rect class="e5tfnwbmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chess-king" /></template>
<style>
.e5tfnwbmk {
  width: 14px;
  height: 2.75px;
  x: 5px;
  y: 18.5px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n0vqr9bmc {
  d: path("M12 2.75v4M10.25 4.5h3.5M9 7.75h6a1 1 0 0 1 .95 1.32L15 11.5c0 1.6.6 3 1.5 4h-9c.9-1 1.5-2.4 1.5-4l-.95-2.43A1 1 0 0 1 9 7.75m.5 3.75h5");
}

</style>
