<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jatasi_5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-symbol-rock" /></template>
<style>
.jatasi_5d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4 15l4.5-7.5L11 11l3.5-7L20 15M2.5 19.5q2.375-2 4.75 0t4.75 0t4.75 0t4.75 0");
}

</style>
