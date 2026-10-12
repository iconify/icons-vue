<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="jl4903ezj"/><circle class="fbfyvgbuo"/><path class="olluzpb6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:creator-studio-sharp" /></template>
<style>
.fbfyvgbuo {
  cx: 12px;
  cy: 9.25px;
  r: 4.15px;
}

.jl4903ezj {
  cx: 12px;
  cy: 9.25px;
  r: 6.5px;
}

.olluzpb6d {
  d: path("M10.5 7.75h3v3h-3zm1.5 8v5.5m-4 0l4-2.75l4 2.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
