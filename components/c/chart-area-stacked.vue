<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j_q_y1bdx"/><path class="nv-yovrvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-area-stacked" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j_q_y1bdx {
  d: path("M3.5 3.5v17h17");
}

.nv-yovrvp {
  d: path("M7 15v-.573a1.5 1.5 0 0 1 .829-1.342l2.549-1.274a1.5 1.5 0 0 1 1.261-.037l2.064.884a1.5 1.5 0 0 0 1.491-.178l1.306-.98a1.25 1.25 0 0 1 2 1V15a1.5 1.5 0 0 1-1.5 1.5H8.5A1.5 1.5 0 0 1 7 15m0-5.5l4-3l3.5 2l4-4");
}

</style>
