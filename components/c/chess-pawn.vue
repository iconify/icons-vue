<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="wv5f_1brg"/><path class="b157_qude"/><rect class="e5tfnwbmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chess-pawn" /></template>
<style>
.b157_qude {
  d: path("M9.25 10.25h5.5L14 11.5c0 1.4.9 2.6 2 4H8c1.1-1.4 2-2.6 2-4Z");
}

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

.wv5f_1brg {
  cx: 12px;
  cy: 5.25px;
  r: 2.5px;
}

</style>
