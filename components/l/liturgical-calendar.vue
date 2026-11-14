<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncwu50gmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:liturgical-calendar" /></template>
<style>
.ncwu50gmj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4.5h17V21h-17Zm4.5-2v4m8-4v4M3.5 9.25h17M8.5 12v6.25M6.25 14h4.5m2.75-.5h4m-4 3.5h3");
}

</style>
