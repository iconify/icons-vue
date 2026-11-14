<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m7g477vdf"/><path class="wu4jel-xu"/><path class="rumiejzbe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:banknote-stack" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m7g477vdf {
  d: path("M5.125 10h8.75a2.625 2.625 0 0 1 2.625 2.625v3.75A2.625 2.625 0 0 1 13.875 19h-8.75A2.625 2.625 0 0 1 2.5 16.375v-3.75A2.625 2.625 0 0 1 5.125 10");
}

.rumiejzbe {
  d: path("M8 4.5h12.5A1.5 1.5 0 0 1 22 6v7.5M8 10v9m3-9v9");
}

.wu4jel-xu {
  d: path("M5.25 7.25h12.5a1.5 1.5 0 0 1 1.5 1.5v7.5");
}

</style>
