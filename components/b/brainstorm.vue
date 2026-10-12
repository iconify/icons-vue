<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p8bmj_5jp"/><path class="ix0zgii_h"/><circle class="tbv1ubc9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:brainstorm" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ix0zgii_h {
  d: path("M10 11a2.5 2.5 0 1 1 3.5 0v1.25H10Z");
}

.p8bmj_5jp {
  d: path("M7 15.5a4 4 0 0 1-.6-7.95a5.5 5.5 0 0 1 10.2-.75a4.35 4.35 0 0 1 .15 8.7Z");
}

.tbv1ubc9c {
  cx: 6.5px;
  cy: 19.25px;
  r: 1.5px;
}

</style>
