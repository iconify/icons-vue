<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bnjc-j_of"/><path class="b2_wbmb6v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:awareness-survey" /></template>
<style>
.b2_wbmb6v {
  d: path("M10 2h4a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 14 5h-4a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 10 2M7.5 9l1.25 1l2-2M7.5 13.5l1.25 1l2-2M7.5 18l1.25 1l2-2m2.5-8h3.25m-3.25 4.5h3.25M13.25 18h3.25");
}

.bnjc-j_of {
  d: path("M8 3.5h8A3.5 3.5 0 0 1 19.5 7v11a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 18V7A3.5 3.5 0 0 1 8 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
