<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8wly31iy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:energy-saving-tips" /></template>
<style>
.i8wly31iy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 16v-1.5a6 6 0 1 1 6 0V16Zm.5 2.75h5M9 21.5h3m1-2.75Q16 16 21 17q-2 4.5-8 1.75");
}

</style>
