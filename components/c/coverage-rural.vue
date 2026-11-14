<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-1a74bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coverage-rural" /></template>
<style>
.z-1a74bnt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5Q7 14 12 18q4.5-4.5 9.5 0m-5-2.25V7.5m-1.75-2a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m4.932-3.182a4.5 4.5 0 0 1 0 6.364m-6.364 0a4.5 4.5 0 0 1 0-6.364");
}

</style>
