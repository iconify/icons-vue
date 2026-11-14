<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="in8f_m3iy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:banding-wheel" /></template>
<style>
.in8f_m3iy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7.5a9.5 3.5 0 1 0 19 0a9.5 3.5 0 1 0-19 0M12 11v6.5m-3.75 0h7.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 15.75 21h-7.5a1.75 1.75 0 0 1-1.75-1.75a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
