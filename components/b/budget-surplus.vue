<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jl94hde-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:budget-surplus" /></template>
<style>
.jl94hde-f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 9h1a1.5 1.5 0 0 1 1.5 1.5V12A1.5 1.5 0 0 1 5 13.5H4A1.5 1.5 0 0 1 2.5 12v-1.5A1.5 1.5 0 0 1 4 9m6.75-3h1a1.5 1.5 0 0 1 1.5 1.5V12a1.5 1.5 0 0 1-1.5 1.5h-1a1.5 1.5 0 0 1-1.5-1.5V7.5a1.5 1.5 0 0 1 1.5-1.5m6.75-3.5h1A1.5 1.5 0 0 1 20 4v8a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 16 12V4a1.5 1.5 0 0 1 1.5-1.5m1 13.75v5.5M15.75 19h5.5");
}

</style>
