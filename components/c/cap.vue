<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tkcgjueox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cap" /></template>
<style>
.tkcgjueox {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 14.75V13a7 7 0 0 1 14 0v1.75Zm7-7.25v7m-7 4A1.25 1.25 0 0 1 5 17.25h14.5a1.75 1.75 0 0 1 0 3.5H5a1.25 1.25 0 0 1-1.25-1.25Z");
}

</style>
