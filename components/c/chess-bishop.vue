<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zrmk1hn6b"/><rect class="e5tfnwbmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chess-bishop" /></template>
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

.zrmk1hn6b {
  d: path("M12 2.75c2.4 1.8 4 3.9 4 6.25a4 4 0 0 1-2.4 3.67c.35 1.15 1.25 2.2 2.65 2.83h-8.5c1.4-.63 2.3-1.68 2.65-2.83A4 4 0 0 1 8 9c0-2.35 1.6-4.45 4-6.25m2 3.5L11.5 9");
}

</style>
