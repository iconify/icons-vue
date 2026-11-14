<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jmilqbbwv"/><path class="b_kid9bdk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:achievement-locked" /></template>
<style>
.b_kid9bdk {
  d: path("M7 13.75v7.75l3-2l2.45 1.633m.55-4.472V13.75M7 8.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m9.75 9h2.5A1.75 1.75 0 0 1 21 19.25v.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 15 19.75v-.5a1.75 1.75 0 0 1 1.75-1.75m-.25 0v-1a1.5 1.5 0 0 1 3 0v1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jmilqbbwv {
  d: path("M4 8.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0");
}

</style>
