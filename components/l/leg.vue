<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fphzfsb6v"/><path class="h6yr5qbzk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leg" /></template>
<style>
.fphzfsb6v {
  d: path("M5 2.5q.75 5.25 3 9c.75 1.5.5 4 .75 7v2c0 .6.4 1 1 1h9c1 0 1.5-1 .75-1.75c-1-1-3-1.5-5.25-2l-1.75-.5c-.25-2.25.25-3.75 1.25-5.5c1-2 .5-5.75-.5-9.25");
}

.h6yr5qbzk {
  d: path("M13.75 11.75q-1.5-.375-2.25-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
