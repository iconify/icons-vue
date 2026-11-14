<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xcfzcps5x"/><path class="buk9p3bcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fly-rod" /></template>
<style>
.buk9p3bcz {
  d: path("M7.25 19.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0M13.5 3c5.5-.5 8 3.5 5 6.5c-2.5 2.5-3 5.5 1 6.5m0 0h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xcfzcps5x {
  d: path("M7.412 16.008za1.25 1.25 0 0 1 .605 1.661l-1.268 2.719a1.25 1.25 0 0 1-1.661.604a1.25 1.25 0 0 1-.605-1.661l1.268-2.719a1.25 1.25 0 0 1 1.661-.604M7.5 16l6-13");
}

</style>
