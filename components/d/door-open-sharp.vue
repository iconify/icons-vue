<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="xuwjnbqhw"/><path class="o57ttnb9p"/><path class="dph_vej6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:door-open-sharp" /></template>
<style>
.dph_vej6h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 6.5h3");
}

.o57ttnb9p {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 12.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xuwjnbqhw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 2.75h13.5v18.5H5.25z");
}

</style>
