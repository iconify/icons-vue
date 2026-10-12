<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="usd4pibih"/><path class="qeut5bb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:handshake-sharp" /></template>
<style>
.qeut5bb9x {
  d: path("M2.75 14.75H5.5l2.12 2.12l1.238.999l2.25-2.25l-1.238-.999M7.75 12.5l2.47 2.47l1.238.999l2.25-2.25l-1.238-.999M10 10.25l2.65 2.65l1.238.999l2.25-2.25l-1.238-.999");
}

.usd4pibih {
  d: path("M2.75 6.75v8.5m18.5-8.5v8m0-6.75h-3.5l-3-1.75l-1.065-.623l-1.035.673L9.6 8.4a1.4 1.4 0 0 0 1.55 2.3l2.35-1.45L18 13.5h3.25M2.75 8H5.5l2.25-1.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
