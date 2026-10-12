<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="axrqm4b_v"/><rect class="yiiwqh1dm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chromosome" /></template>
<style>
.axrqm4b_v {
  d: path("M5.25 5a1.75 1.75 0 0 1 3.4-.6c.9 2.9 1.6 4.85 1.6 7.6s-.7 4.7-1.6 7.6a1.75 1.75 0 0 1-3.4-.6C6 16.4 6.5 14.85 6.5 12S6 7.6 5.25 5m13.5 0a1.75 1.75 0 0 0-3.4-.6c-.9 2.9-1.6 4.85-1.6 7.6s.7 4.7 1.6 7.6a1.75 1.75 0 0 0 3.4-.6c-.75-2.6-1.25-4.15-1.25-7s.5-4.4 1.25-7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yiiwqh1dm {
  width: 6.5px;
  height: 2.5px;
  x: 8.75px;
  y: 10.75px;
  rx: 1.25px;
}

</style>
