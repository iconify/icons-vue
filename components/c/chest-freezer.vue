<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sf2z3nbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chest-freezer" /></template>
<style>
.sf2z3nbwr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 10.5h12a3.5 3.5 0 0 1 3.5 3.5v4a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 18v-4A3.5 3.5 0 0 1 6 10.5M3.39 5.35l16.339-2.296a1.25 1.25 0 0 1 1.412 1.064a1.25 1.25 0 0 1-1.064 1.412L3.738 7.826a1.25 1.25 0 0 1-1.412-1.064A1.25 1.25 0 0 1 3.39 5.35m8.61 7.9v5.5M9.5 14.5l5 3m-5 0l5-3");
}

</style>
