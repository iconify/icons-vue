<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="st7yyjbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:binoculars-marine" /></template>
<style>
.st7yyjbvl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 8za4 4 0 0 1 4 4v5.5a4 4 0 0 1-4 4a4 4 0 0 1-4-4V12a4 4 0 0 1 4-4m11 0za4 4 0 0 1 4 4v5.5a4 4 0 0 1-4 4a4 4 0 0 1-4-4V12a4 4 0 0 1 4-4M5.75 3h1.5A1.75 1.75 0 0 1 9 4.75v1.5A1.75 1.75 0 0 1 7.25 8h-1.5A1.75 1.75 0 0 1 4 6.25v-1.5A1.75 1.75 0 0 1 5.75 3m11 0h1.5A1.75 1.75 0 0 1 20 4.75v1.5A1.75 1.75 0 0 1 18.25 8h-1.5A1.75 1.75 0 0 1 15 6.25v-1.5A1.75 1.75 0 0 1 16.75 3m-6.25 9h3");
}

</style>
