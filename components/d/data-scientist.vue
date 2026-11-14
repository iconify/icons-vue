<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0r_j42zu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-scientist" /></template>
<style>
.h0r_j42zu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.872 21H4.5c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c.789 0 1.543.078 2.249.225M7 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m11 6.75za1 1 0 0 1 1 1v1.361a1.5 1.5 0 0 0 .189.729l1.073 1.932a1.5 1.5 0 0 1-1.311 2.228h-1.902a1.5 1.5 0 0 1-1.311-2.228l1.073-1.932a1.5 1.5 0 0 0 .189-.729V15.25a1 1 0 0 1 1-1m-2 0h4");
}

</style>
