<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gln3-pb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:free-samples" /></template>
<style>
.gln3-pb7m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4H15M3.5 4l1.75 15.5h7L14 4m4.75 9Q19 16.25 22 16.5q-3 .25-3.25 3.5q-.25-3.25-3.25-3.5q3-.25 3.25-3.5");
}

</style>
