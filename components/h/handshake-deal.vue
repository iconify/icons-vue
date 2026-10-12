<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o1ecxbclh"/><path class="h8v2p4pya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:handshake-deal" /></template>
<style>
.h8v2p4pya {
  d: path("M2.75 17.25H5.5l2.12 2.12a1.6 1.6 0 0 0 2.25-2.25M7.75 15l2.47 2.47a1.6 1.6 0 0 0 2.25-2.25M10 12.75l2.65 2.65a1.6 1.6 0 0 0 2.25-2.25m-5.65-8.9l2 2l3.5-3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o1ecxbclh {
  d: path("M2.75 9.25v8.5m18.5-8.5v8m0-6.75h-3.5l-3-1.75a2 2 0 0 0-2.1.05L9.6 10.9a1.4 1.4 0 0 0 1.55 2.3l2.35-1.45L18 16h3.25m-18.5-5.5H5.5l2.25-1.25");
}

</style>
