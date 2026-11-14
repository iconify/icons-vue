<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w1fib_b8r"/><path class="q7zy78b8u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:git-revert" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q7zy78b8u {
  d: path("M7 4.5L3.5 8L7 11.5m.25 7.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.w1fib_b8r {
  d: path("M3.5 8h12a5.5 5.5 0 0 1 0 11h-4.25");
}

</style>
