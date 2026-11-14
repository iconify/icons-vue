<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lkp5d94cu"/><path class="c1jyvo6mx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car-dimensions" /></template>
<style>
.c1jyvo6mx {
  d: path("M5 12.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-12 7h18m-16-2l-2 2l2 2m14-4l2 2l-2 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lkp5d94cu {
  d: path("M5 12.5H3.5q-1 0-1-1v-3l3-1.5L8 3h7.5l3 4l2 .5q1 .25 1 1.25v2.75q0 1-1 1H19m-10 0h6");
}

</style>
