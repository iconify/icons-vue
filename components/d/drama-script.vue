<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xvwpytbld"/><path class="hyc08fbbb"/><path class="jf16a4ymc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drama-script" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hyc08fbbb {
  d: path("M7.5 8.75q4.5 1.5 9 0v2.75c0 2.75-2 4.75-4.5 4.75s-4.5-2-4.5-4.75Zm2.5 2.5h.01m3.99 0h.01");
}

.jf16a4ymc {
  d: path("M9.75 13.5q2.25 1.5 4.5 0M9.5 19h5");
}

.xvwpytbld {
  d: path("M16 2.5H6.75A2.25 2.25 0 0 0 4.5 4.75v14.5a2.25 2.25 0 0 0 2.25 2.25h10.5a2.25 2.25 0 0 0 2.25-2.25V6Zm0 0V6h3.5");
}

</style>
