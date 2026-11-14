<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op1n5nbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:building-crane-toy" /></template>
<style>
.op1n5nbnw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 6.5v15h4.5v-15M3 6.5h18m-16 0l2.25-4l5.75 4m5 0V11a1.5 1.5 0 0 1-3 0m-.5 5h6v5.5h-6Z");
}

</style>
