<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qrgolwbrj"/><path class="e7yjx9bjy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:floor-cushion" /></template>
<style>
.e7yjx9bjy {
  d: path("M3 9.5v3a9 3.5 0 0 0 18 0v-3m-18.5 10h19M12 9.5h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qrgolwbrj {
  d: path("M3 9.5a9 3.5 0 1 0 18 0a9 3.5 0 1 0-18 0");
}

</style>
