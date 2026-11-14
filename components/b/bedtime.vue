<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcv78_h_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bedtime" /></template>
<style>
.tcv78_h_u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.5 15.5a7.5 7.5 0 1 1-9-9.5a6 6 0 0 0 9 9.5M15.5 3H20l-4.5 4.5H20");
}

</style>
