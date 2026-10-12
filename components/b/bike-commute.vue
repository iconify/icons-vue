<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="xdhqn2b4q"/><circle class="k-bx946ur"/><path class="j8lzq0dce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bike-commute" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j8lzq0dce {
  d: path("M6 16.25L9 10h7m2 6.25l-2.75-9h2.25M9 10l3.5 6.25H6M9 10l.5-2.75m-1.25 0h2.5m6.75-.5c.25-2.25 1.25-3.25 3.5-3.5c-.25 2.25-1.25 3.25-3.5 3.5");
}

.k-bx946ur {
  cx: 18px;
  cy: 16.25px;
  r: 3.25px;
}

.xdhqn2b4q {
  cx: 6px;
  cy: 16.25px;
  r: 3.25px;
}

</style>
