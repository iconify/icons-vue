<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ao1pd8bew"/><path class="e7xy8ib5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-stream" /></template>
<style>
.ao1pd8bew {
  d: path("M2.5 6q3-3 6 0t6 0t6 0m-18 6q3-3 6 0t6 0t6 0m-18 6q3-3 6 0t6 0t6 0");
}

.e7xy8ib5q {
  d: path("m19.75 3.75l1 2.25l-2.25 1m1.25 2.75l1 2.25l-2.25 1m1.25 2.75l1 2.25l-2.25 1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
