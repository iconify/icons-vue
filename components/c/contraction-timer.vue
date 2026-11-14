<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2zp6lbtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:contraction-timer" /></template>
<style>
.z2zp6lbtm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15.5C4.75 15.5 5 5 7 5s2.25 10.5 4.25 10.5S13.5 3 15.75 3c1.363 0 1.992 4.585 2.776 8.201M14.75 18.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0ZM18 14v1.25m0 3.25l1.25-1.25");
}

</style>
