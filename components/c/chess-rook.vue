<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e-3jdcc3e"/><rect class="e5tfnwbmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chess-rook" /></template>
<style>
.e-3jdcc3e {
  d: path("M7.5 3h1.25q.5 0 .5.5v1q0 .5.5.5h.65q.5 0 .5-.5v-1q0-.5.5-.5h1.2q.5 0 .5.5v1q0 .5.5.5h.65q.5 0 .5-.5v-1q0-.5.5-.5h1.25q.5 0 .5.5v4q0 .5-.35.85l-.8.8q-.35.35-.35.85v5q0 .5-.5.5H9q-.5 0-.5-.5v-5q0-.5-.35-.85l-.8-.8Q7 8 7 7.5v-4q0-.5.5-.5m1.25 6.5h6.5");
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

</style>
