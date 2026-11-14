<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aah198p-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:assembly-line" /></template>
<style>
.aah198p-c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 14.5h14a2.5 2.5 0 0 1 2.5 2.5a2.5 2.5 0 0 1-2.5 2.5H5A2.5 2.5 0 0 1 2.5 17A2.5 2.5 0 0 1 5 14.5m.5 2.5h.01m12.99 0h.01M5.25 5.5h2.5A1.75 1.75 0 0 1 9.5 7.25V9a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 3.5 9V7.25A1.75 1.75 0 0 1 5.25 5.5m11 0h2.5a1.75 1.75 0 0 1 1.75 1.75V9a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 14.5 9V7.25a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
