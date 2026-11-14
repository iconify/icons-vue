<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l0jr_2xyc"/><path class="b7o1kbcmt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:backstage-pass" /></template>
<style>
.b7o1kbcmt {
  d: path("M10 13.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-.5 4.75h5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l0jr_2xyc {
  d: path("M10 9h4a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-4A3.5 3.5 0 0 1 6.5 18v-5.5A3.5 3.5 0 0 1 10 9M8.5 9l2.75-5.5q.75-1.5 1.5 0L15.5 9");
}

</style>
