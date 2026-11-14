<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j_q_y1bdx"/><path class="vgd-tsbyq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-area" /></template>
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

.vgd-tsbyq {
  d: path("M7 15v-2.319a1.5 1.5 0 0 1 .512-1.129l2.51-2.197a1.5 1.5 0 0 1 1.964-.01l1.336 1.145a1.5 1.5 0 0 0 2.147-.202L16.5 9a1.123 1.123 0 0 1 2 .702V15a1.5 1.5 0 0 1-1.5 1.5H8.5A1.5 1.5 0 0 1 7 15");
}

</style>
