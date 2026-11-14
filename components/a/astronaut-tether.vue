<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jbp-58bbs"/><path class="zf1_uk4-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:astronaut-tether" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jbp-58bbs {
  d: path("M2.5 15V9.5a7 7 0 0 1 14 0V15M4 15h11a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 17v-.5A1.5 1.5 0 0 1 4 15");
}

.zf1_uk4-c {
  d: path("M16.5 11.5c3 0 5 2 5 4.5c0 3.5-2.75 5.5-5.5 5.5M6 9.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>
