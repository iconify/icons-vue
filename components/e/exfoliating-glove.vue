<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruc-7_z3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:exfoliating-glove" /></template>
<style>
.ruc-7_z3l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 20.5v-12c0-2.8 2.2-5 5-5s5 2.2 5 5V11l2-1.5c1-.75 2.4.1 2 1.5l-4 7v2.5Zm3-12h.01m3.99 0h.01M8 12.5h.01m3.99 0h.01M5 17h10");
}

</style>
