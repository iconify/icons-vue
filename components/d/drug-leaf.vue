<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyjq24j6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drug-leaf" /></template>
<style>
.oyjq24j6w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 17C4 9 9 3 19 3c0 10-6 15-14 14m0 0l-2.5 2.5M5 17l7.5-7.5m3.025 8.25L18 15.275a1.75 1.75 0 0 1 2.475 0a1.75 1.75 0 0 1 0 2.475L18 20.225a1.75 1.75 0 0 1-2.475 0a1.75 1.75 0 0 1 0-2.475m1.238-1.237l2.474 2.474");
}

</style>
