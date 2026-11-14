<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k51rv8_9r"/><path class="hbdwe-b5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dark-beer" /></template>
<style>
.hbdwe-b5w {
  d: path("M5.75 7.5q1.75 2 3.25 0t3 0t3 0t3.25 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k51rv8_9r {
  d: path("M8.353 3h7.294a2.625 2.625 0 0 1 2.616 2.843l-1.062 12.75A2.625 2.625 0 0 1 14.585 21h-5.17a2.625 2.625 0 0 1-2.616-2.407L5.737 5.843A2.625 2.625 0 0 1 8.353 3");
}

</style>
