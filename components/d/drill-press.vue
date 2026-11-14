<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugr8c_bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drill-press" /></template>
<style>
.ugr8c_bgb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 19h9.5A1.25 1.25 0 0 1 16 20.25a1.25 1.25 0 0 1-1.25 1.25h-9.5A1.25 1.25 0 0 1 4 20.25A1.25 1.25 0 0 1 5.25 19M7 19V4m.5-1.5h7A2.5 2.5 0 0 1 17 5a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 5 5a2.5 2.5 0 0 1 2.5-2.5m6.5 5v4m-4.5 3H18M17 5l3.5 2.5");
}

</style>
