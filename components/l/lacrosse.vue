<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v0hedtnwf"/><circle class="m-6tq_x6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lacrosse" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m-6tq_x6h {
  cx: 17.5px;
  cy: 17.5px;
  r: 2.25px;
}

.v0hedtnwf {
  d: path("m12.2 11.2l-1.8-4.6c-.5-1.3-.2-2.7.9-3.4c1.3-.7 2.9-.3 4.4.5l4.1 2.4c1.2.7 1.7 2.2 1 3.5c-.6 1.1-2 1.4-3.4 1.1l-4.6 1.1Zm.8-5.95l5.25 3m-5.5.25l2.75-3.25m-3 6.25l-9.25 9.25");
}

</style>
