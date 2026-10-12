<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="jg7xt1_6k"/><path class="b9rb1bbyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:glowing-skin" /></template>
<style>
.b9rb1bbyy {
  d: path("M6.75 13c.55.65 1.45.65 2 0m2.5 0c.55.65 1.45.65 2 0M8.5 16.75q1.5 1.125 3 0m6.5-14c.4 2 1.25 2.85 3.25 3.25c-2 .4-2.85 1.25-3.25 3.25c-.4-2-1.25-2.85-3.25-3.25c2-.4 2.85-1.25 3.25-3.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jg7xt1_6k {
  cx: 10px;
  cy: 14px;
  r: 7.25px;
}

</style>
