<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rggtr-vux"/><path class="mcjc66ify"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dune-sharp" /></template>
<style>
.mcjc66ify {
  d: path("m16.25 14.5l-.404 2.423l-1.096 1.827M2.75 7.5c2.5 0 4.5-.75 7.25-.75m-4.75 4.5c1.75 0 3-.5 5-.5");
}

.rggtr-vux {
  d: path("M2.75 21.25V19.5c4.75-1.5 9.25-4.25 13.5-8c1.25 3.25 2.75 6.25 5 8v1.75Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
