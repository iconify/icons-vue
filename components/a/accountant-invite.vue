<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oh6bzhbbg"/><path class="i0x91lukr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:accountant-invite" /></template>
<style>
.i0x91lukr {
  d: path("m2.5 6l9 5.5l9-5.5M18 14.5v7M14.5 18h7");
}

.oh6bzhbbg {
  d: path("M11.7 17H2.5V3.5h18v8.2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
