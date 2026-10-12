<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcjsc7bcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:breeze-sharp" /></template>
<style>
.zcjsc7bcz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9.5Q5 7 7.25 9.5t4.5 0m-9 5.5q2.25-2.5 4.5 0t4.5 0t4.5 0t4.5 0m-6-4.75c0-4.25 2.25-6.75 6.5-7c0 4.25-2.25 7-6.5 7Z");
}

</style>
