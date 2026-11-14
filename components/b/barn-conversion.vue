<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vmh-p1bkt"/><path class="vdaykcb5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:barn-conversion" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vdaykcb5d {
  d: path("M10 9.5h4a1.5 1.5 0 0 1 1.5 1.5v9a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 8.5 20v-9A1.5 1.5 0 0 1 10 9.5m2 0v12m-3.5-6h7");
}

.vmh-p1bkt {
  d: path("M3 20v-8.618a1.5 1.5 0 0 1 .183-.718l2.592-4.751a1.5 1.5 0 0 1 .646-.623l4.908-2.455a1.5 1.5 0 0 1 1.342 0l4.908 2.455a1.5 1.5 0 0 1 .646.623l2.592 4.751a1.5 1.5 0 0 1 .183.718V20a1.5 1.5 0 0 1-1.5 1.5h-15A1.5 1.5 0 0 1 3 20");
}

</style>
