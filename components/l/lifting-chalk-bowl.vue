<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jar2hqmam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lifting-chalk-bowl" /></template>
<style>
.jar2hqmam {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11h18c0 5-4 8.5-9 8.5S3 16 3 11Zm3.5 0c1-5 3.5-7 5.5-7s4.5 2 5.5 7");
}

</style>
