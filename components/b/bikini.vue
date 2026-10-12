<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwhqvsk9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bikini" /></template>
<style>
.bwhqvsk9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.14 9.36l2.72-4.47q.39-.64.71.04l2.11 4.39q.32.68-.43.68H5.5q-.75 0-.36-.64m8.18-.04l2.11-4.39q.32-.68.71-.04l2.72 4.47q.39.64-.36.64h-4.75q-.75 0-.43-.68M2.75 10h2M11 10h2m6.25 0h2m-16.5 3.5h14.5L19 14.75c-2.5.75-4.25 2.75-5 6.5h-4c-.75-3.75-2.5-5.75-5-6.5Z");
}

</style>
