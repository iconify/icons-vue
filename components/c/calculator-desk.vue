<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eoz3zibrm"/><path class="p73fa6bca"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calculator-desk" /></template>
<style>
.eoz3zibrm {
  d: path("M4.5 2.5h15v19h-15Z");
}

.p73fa6bca {
  d: path("M8 5.5h8v4H8Zm.5 8h.01m3.49 0h.01m3.49 0h.01m-7.01 4h.01m3.49 0h.01m3.49 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
