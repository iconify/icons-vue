<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pld7uqgwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:battle-ropes" /></template>
<style>
.pld7uqgwz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.5q2.25-3 4.5 0c2.25 3 3 2 4.5 0s3-2 4.5 0c1.25 1.6 3 3.6 4.75 4.5M2.75 16.5q2.25 3 4.5 0c2.25-3 3-2 4.5 0s3 2 4.5 0c1.25-1.6 3-3.6 4.75-4.5m.25-6.5v13");
}

</style>
