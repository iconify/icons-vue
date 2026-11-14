<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tu-ro5q3a"/><path class="lhn3cpxsj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heart-box-chocolates" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lhn3cpxsj {
  d: path("m12 17.5l-3-3a2.125 2.125 0 0 1 3-3a2.125 2.125 0 0 1 3 3Z");
}

.tu-ro5q3a {
  d: path("M4.688 3.5h14.625A2.19 2.19 0 0 1 21.5 5.688v.125A2.19 2.19 0 0 1 19.313 8H4.688A2.19 2.19 0 0 1 2.5 5.813v-.125A2.19 2.19 0 0 1 4.688 3.5M4 8v11.5q0 1.25 1.25 1.25h13.5q1.25 0 1.25-1.25V8");
}

</style>
