<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d19cl7bee"/><rect class="k05evjbyu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:catalytic-converter" /></template>
<style>
.d19cl7bee {
  d: path("M3.5 10.75h1.75q.75 0 1.1-.66l1.3-2.43Q8 7 8.75 7h6.5q.75 0 1.1.66l1.3 2.43q.35.66 1.1.66h1.75q.75 0 .75.75v1q0 .75-.75.75h-1.75q-.75 0-1.1.66l-1.3 2.43q-.35.66-1.1.66h-6.5q-.75 0-1.1-.66l-1.3-2.43q-.35-.66-1.1-.66H3.5q-.75 0-.75-.75v-1q0-.75.75-.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k05evjbyu {
  width: 5px;
  height: 4.5px;
  x: 9.5px;
  y: 9.75px;
  rx: 1px;
}

</style>
