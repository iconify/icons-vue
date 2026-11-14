<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6pqcrbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cleared-for-takeoff" /></template>
<style>
.u6pqcrbwq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.39 16.404l-2.744-4.679l-1.944 1.944l.177 2.652l-.707.707l-1.945-3.005l-3.005-1.945l.707-.707l2.652.177l1.944-1.944l-5.126-3.006l1.414-1.414l6.541 1.591l2.298-2.298l2.475-.354l-.354 2.475l-2.298 2.298l1.454 5.976M2.5 20.5H11m3.75-2.5l2 2L21 15.75");
}

</style>
