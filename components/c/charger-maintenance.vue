<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="olz-o_b1z"/><path class="f0me3hbjv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:charger-maintenance" /></template>
<style>
.f0me3hbjv {
  d: path("M10.5 15.5v3a3 3 0 0 1-3 3H3m4.75-19V6m5.5-3.5V6m6.25 8a2.5 2.5 0 1 0 2.5 2.5h-2.5Zm-1.75 4.25L14.5 21.5");
}

.olz-o_b1z {
  d: path("M4.5 6h12v3.5a6 6 0 0 1-12 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
