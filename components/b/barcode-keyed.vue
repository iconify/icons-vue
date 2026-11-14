<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mr96k827r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:barcode-keyed" /></template>
<style>
.mr96k827r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4.5V12m3-7.5V12m3-7.5V12m3-7.5V12m3-7.5V12m3-7.5V12M6 17h.01M12 17h.01M18 17h.01");
}

</style>
