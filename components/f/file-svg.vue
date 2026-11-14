<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_a5jubhp"/><path class="kd73rjbgi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:file-svg" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kd73rjbgi {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4M9 16.75zA1.25 1.25 0 0 1 10.25 18A1.25 1.25 0 0 1 9 19.25A1.25 1.25 0 0 1 7.75 18A1.25 1.25 0 0 1 9 16.75m6.25-6.25za1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 15.25 13A1.25 1.25 0 0 1 14 11.75a1.25 1.25 0 0 1 1.25-1.25M9 16.75c0-3.25 2-5 5-5");
}

.w_a5jubhp {
  d: path("M7 2.5h6.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5");
}

</style>
