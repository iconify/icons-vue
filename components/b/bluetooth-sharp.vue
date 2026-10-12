<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="g1ztaob7y"/><path class="mifla9vvb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bluetooth-sharp" /></template>
<style>
.g1ztaob7y {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.75 7.25l10.5 9.5l-5.25 4.5V2.75l5.25 4.5l-10.5 9.5");
}

.mifla9vvb {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.5 12h.01m16.99 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
