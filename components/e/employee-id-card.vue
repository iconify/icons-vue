<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="guxyen-_b"/><path class="vwwim0brd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:employee-id-card" /></template>
<style>
.guxyen-_b {
  d: path("M8 6.5h8a3.5 3.5 0 0 1 3.5 3.5v7a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 17v-7A3.5 3.5 0 0 1 8 6.5M10 3h4m-2 0v3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vwwim0brd {
  d: path("M10 11.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0M8.5 18a3.5 3 0 0 1 7 0");
}

</style>
