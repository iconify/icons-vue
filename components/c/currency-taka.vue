<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apdr7yleu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:currency-taka" /></template>
<style>
.apdr7yleu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 6c0-1 .9-1.75 1.75-1.5c1 .25 1.25 1.25 1.25 2.5v8.5c0 2.25 1.75 4 4 4s4-1.75 4-4c0-2-1.25-3.25-2.75-3.25M6.5 9.5H13");
}

</style>
