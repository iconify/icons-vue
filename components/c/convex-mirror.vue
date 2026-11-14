<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mcfo0f-ee"/><path class="zd4_f1f_i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:convex-mirror" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mcfo0f-ee {
  d: path("M21 2.5q-8 9.5 0 19");
}

.zd4_f1f_i {
  d: path("M3 9h14.5L9 3.5M3 15h14.5L9 20.5");
}

</style>
