<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="jl4903ezj"/><path class="a6ox1ojiz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:badge-check-sharp" /></template>
<style>
.a6ox1ojiz {
  d: path("m9.5 9.5l1.75 1.75l3.25-3.5M8.5 15l-1.25 6.25L12 19l4.75 2.25L15.5 15");
}

.jl4903ezj {
  cx: 12px;
  cy: 9.25px;
  r: 6.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
