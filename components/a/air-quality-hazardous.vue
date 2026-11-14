<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kt_46cb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:air-quality-hazardous" /></template>
<style>
.kt_46cb4b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.5c2-2 4.25-2 6.25 0s4.25 2 6.25 0s4.25-2 6.25 0M2.5 9.5c2-2 4.25-2 6.25 0s4.25 2 6.25 0s4.25-2 6.25 0M2.5 15c1.75-2 3.5-2 5 0s3.25 2 5 0m2.75 2.5a3.25 3.25 0 0 1 6.5 0c0 1.25-.75 2-1.5 2.25v1.75h-3.5v-1.75c-.75-.25-1.5-1-1.5-2.25m2 .25h.01m2.49 0h.01");
}

</style>
