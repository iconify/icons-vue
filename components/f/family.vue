<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="t6ozvr6zj"/><circle class="z1qpurb8m"/><path class="qnrk4qblw"/><circle class="yjztigbem"/><path class="ayw990bzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:family" /></template>
<style>
.ayw990bzt {
  d: path("M10.75 20.5v-1.75a1.25 1.25 0 0 1 2.5 0v1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qnrk4qblw {
  d: path("M2.75 20.5V17a2.5 2.5 0 0 1 5 0v3.5m8.5 0V17a2.5 2.5 0 0 1 5 0v3.5");
}

.t6ozvr6zj {
  cx: 5.25px;
  cy: 9px;
  r: 2.5px;
}

.yjztigbem {
  cx: 12px;
  cy: 12.5px;
  r: 2px;
}

.z1qpurb8m {
  cx: 18.75px;
  cy: 9px;
  r: 2.5px;
}

</style>
