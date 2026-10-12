<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2sar-b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bug-fix" /></template>
<style>
.l2sar-b1x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 8a3.5 5 0 1 1 0 10a3.5 5 0 1 1 0-10m0 3v4m-3.03-4.5L4.72 9.25M6.5 13H4m2.97 2.5l-2.25 1.25m8.31-6.25l2.25-1.25M13.5 13H16m-2.97 2.5l2.25 1.25m.97 3l1.5 1.5l3-3.25");
}

</style>
