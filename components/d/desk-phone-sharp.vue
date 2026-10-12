<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="vhlx4xi6r"/><path class="b3hzthn_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:desk-phone-sharp" /></template>
<style>
.b3hzthn_j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 16.75h.01m3.49 0h.01m3.49 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vhlx4xi6r {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8.25V6.5c0-2 3.75-3.75 8.5-3.75s8.5 1.75 8.5 3.75v2.75H16V7l-1.8-.6H9.8L8 7v2.25H3.5zm2.75 4h13l.25 1.48l1 6.04l.25 1.48H3.25l.25-1.48l1-6.04l.25-1.48z");
}

</style>
