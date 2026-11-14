<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrhynudzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lab-barcode-scanner" /></template>
<style>
.xrhynudzc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5.75a2 2 0 0 1 2-2h7v5.5h-2l-1.25 11.5H4l1.25-11.5H4.5a2 2 0 0 1-2-2Zm14-2.5v11a2.25 2.25 0 0 0 4.5 0v-11m-5.5 0H22M11.5 6.5l5-2m-5 2l5 3");
}

</style>
