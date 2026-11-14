<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8tvgac9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flash-bounce" /></template>
<style>
.d8tvgac9x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h19M5.603 15.996l1.409-2.349a1.5 1.5 0 0 1 2.346-.289l1.284 1.284a1.5 1.5 0 0 1-.289 2.346l-2.349 1.409a1.5 1.5 0 0 1-1.832-.225l-.344-.344a1.5 1.5 0 0 1-.225-1.832M6 18l-2.5 2.5M11 11l5.5-5.5l4 4m-2.75 0h2.75V6.75");
}

</style>
