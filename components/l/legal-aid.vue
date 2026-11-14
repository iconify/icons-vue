<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inndormil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:legal-aid" /></template>
<style>
.inndormil {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 3.5v17m-2 0h4m-8-17h12M2 8l3-4.5L8 8a3 3 0 0 1-6 0m12 0l3-4.5L20 8a3 3 0 0 1-6 0m4 13.5c-3.75-2.5-4-5.5-2.25-6.25c1-.5 1.75.25 2.25 1c.5-.75 1.25-1.5 2.25-1C22 16 21.75 19 18 21.5");
}

</style>
