<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n78kc1bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:catheter" /></template>
<style>
.n78kc1bmi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 7h10a3.5 3.5 0 0 1 3.5 3.5v4A3.5 3.5 0 0 1 16 18H6a3.5 3.5 0 0 1-3.5-3.5v-4A3.5 3.5 0 0 1 6 7m11 0V4.5c0-1.25 1-2 2.25-2h2.25M11 18za1.25 1.25 0 0 1 1.25 1.25v.25A1.25 1.25 0 0 1 11 20.75a1.25 1.25 0 0 1-1.25-1.25v-.25A1.25 1.25 0 0 1 11 18m-6-8h2.5M5 12.5h1.5M5 15h2.5");
}

</style>
