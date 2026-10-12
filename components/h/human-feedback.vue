<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="v9upi9b5t"/><path class="g-ve4ficm"/><path class="jt32-ub8m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:human-feedback" /></template>
<style>
.g-ve4ficm {
  d: path("M2.75 20.75a5.25 5.25 0 0 1 10.5 0m2.5-18h3.5a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2h-1l-2.5 2v-2a2 2 0 0 1-2-2v-3a2 2 0 0 1 2-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jt32-ub8m {
  d: path("M15.75 6.25L17 7.5l2.25-2.25");
}

.v9upi9b5t {
  cx: 8px;
  cy: 8.75px;
  r: 3.25px;
}

</style>
