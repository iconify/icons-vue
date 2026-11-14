<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mfrk4zwvc"/><path class="fe645xucn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cheque-micr" /></template>
<style>
.fe645xucn {
  d: path("M5 14.75h1.75V17H5Zm4.75 0h1V17h-1Zm3.5 0H15v.75h-1.75Zm0 1.75H15v.5h-1.75Zm4.25-1.75H19V17h-1.5Z");
}

.mfrk4zwvc {
  d: path("M2.5 4.5h19v15h-19Zm3 4H12m-6.5 3h4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
