<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqazi6n0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:folk-tale-book" /></template>
<style>
.sqazi6n0r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12v8c3.5-1 7-.5 9.5 1c2.5-1.5 6-2 9.5-1v-8c-3.5-1-7-.5-9.5 1c-2.5-1.5-6-2-9.5-1m9.5 1v8m0-11c-.5-3.5 1-7.25 4.5-7.25c3 0 4.25 3.75 2 5.25c-1.75 1.25-3.75 0-3-1.75");
}

</style>
