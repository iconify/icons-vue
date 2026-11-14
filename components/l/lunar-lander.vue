<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1fbp2c_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lunar-lander" /></template>
<style>
.e1fbp2c_c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.703 3.5h4.594a1.5 1.5 0 0 1 1.153.54l1.702 2.043a1.5 1.5 0 0 1 .348.96V10a1.5 1.5 0 0 1-1.5 1.5H8A1.5 1.5 0 0 1 6.5 10V7.043a1.5 1.5 0 0 1 .348-.96L8.55 4.04a1.5 1.5 0 0 1 1.153-.54m-2.203 8l-3.5 8m12.5-8l3.5 8m-9.75-8l-1 8m4.5-8l1 8m-12.25 0h19");
}

</style>
