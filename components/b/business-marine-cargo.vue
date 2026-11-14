<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_ebp8b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:business-marine-cargo" /></template>
<style>
.w_ebp8b4s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h19L19 16.5H5Zm5-4H10a1.5 1.5 0 0 1 1.5 1.5v1A1.5 1.5 0 0 1 10 12H7.5A1.5 1.5 0 0 1 6 10.5v-1A1.5 1.5 0 0 1 7.5 8M13 8h2.5A1.5 1.5 0 0 1 17 9.5v1a1.5 1.5 0 0 1-1.5 1.5H13a1.5 1.5 0 0 1-1.5-1.5v-1A1.5 1.5 0 0 1 13 8m-2.75-4h2.5a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5h-2.5a1.5 1.5 0 0 1-1.5-1.5v-1a1.5 1.5 0 0 1 1.5-1.5M3 20q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
