<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b8whdzbit"/><path class="xk2xo0boc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:budget-envelope" /></template>
<style>
.b8whdzbit {
  d: path("M6 8.5h12a3.5 3.5 0 0 1 3.5 3.5v5a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 17v-5A3.5 3.5 0 0 1 6 8.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xk2xo0boc {
  d: path("m2.5 9l9.5 5.5L21.5 9M6 8.5v-4a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v4");
}

</style>
