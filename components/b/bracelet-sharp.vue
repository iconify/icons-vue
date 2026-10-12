<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="m9__qepra"/><path class="zxdhbfg8h"/><circle class="dg7n60pmh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bracelet-sharp" /></template>
<style>
.dg7n60pmh {
  cx: 12px;
  cy: 18.5px;
  r: 1.75px;
}

.m9__qepra {
  d: path("M2.75 8.75a9.25 5 0 1 0 18.5 0a9.25 5 0 1 0-18.5 0");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zxdhbfg8h {
  d: path("M2.75 8.75v3a9.25 5 0 0 0 18.5 0v-3");
}

</style>
