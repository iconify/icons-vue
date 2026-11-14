<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="chrea5bat"/><path class="ptorog1oy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ball-peen-hammer" /></template>
<style>
.chrea5bat {
  d: path("m13.945 4.045l3.889 3.889a1.75 1.75 0 0 1 0 2.475l-.707.707a1.75 1.75 0 0 1-2.475 0l-3.889-3.889a1.75 1.75 0 0 1 0-2.475l.707-.707a1.75 1.75 0 0 1 2.475 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ptorog1oy {
  d: path("M13.768 10.232za1.5 1.5 0 0 1 0 2.122L7.05 19.071a1.5 1.5 0 0 1-2.121 0a1.5 1.5 0 0 1 0-2.121l6.717-6.718a1.5 1.5 0 0 1 2.122 0m2.982 2.018a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

</style>
