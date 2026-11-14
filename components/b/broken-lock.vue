<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fesm2hb2j"/><path class="fqr0r3bdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:broken-lock" /></template>
<style>
.fesm2hb2j {
  d: path("M4.5 10.5h15v11h-15Zm4-2.75V6a3.5 3.5 0 0 1 7 0v1.75");
}

.fqr0r3bdv {
  d: path("m4.5 15.5l4.5 2l3-3l3 2.5l4.5-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
