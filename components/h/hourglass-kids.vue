<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n28228bdr"/><path class="q1asy9bbx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hourglass-kids" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n28228bdr {
  d: path("M4.5 3h15m-15 18h15M6.5 3v2.5C6.5 9 12 10 12 12s-5.5 3-5.5 6.5V21m11-18v2.5C17.5 9 12 10 12 12s5.5 3 5.5 6.5V21");
}

.q1asy9bbx {
  d: path("M6.75 18q5.25-3.5 10.5 0");
}

</style>
