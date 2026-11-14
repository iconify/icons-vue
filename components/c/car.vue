<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ggulojbvc"/><path class="h5ayq4b5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car" /></template>
<style>
.ggulojbvc {
  d: path("M2.5 15v-2.25c0-1 .5-1.5 1.5-1.75l2.75-.75l2-3.5Q9.125 6 10.25 6h4.5q1.125 0 1.5.75l2.25 3.5l1.5.5c1 .25 1.5.75 1.5 1.75V15a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 15m4.25-4.75H18.5");
}

.h5ayq4b5f {
  d: path("M5 17.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
