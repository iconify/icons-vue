<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzp2ay52u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:el-nino" /></template>
<style>
.lzp2ay52u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 7.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M12 3.5V2.25m-4.25 5.5H6.5m9.75 0h1.25m-8.5-3l-1-1m7 1l1-1m-7 7l-1 1m7-1l1 1M2.5 15.5q2.5-1.5 5 0t5 0m-10 4q2.5-1.5 5 0t5 0M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

</style>
