<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h5lh_pbav"/><path class="mcmrpc7tv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:knot-sailor" /></template>
<style>
.h5lh_pbav {
  d: path("M2.75 14.5h5a1.5 1.5 0 0 0 1.5-1.5V6.5a2.75 2.75 0 0 1 5.5 0v6a1.5 1.5 0 0 0 1.5 1.5m2.5 0h2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mcmrpc7tv {
  d: path("M2.75 7.5H5A1.5 1.5 0 0 1 6.5 9v4m.37 3a5.5 5.5 0 0 0 10.63-2V9.5A1.5 1.5 0 0 1 19 8h2.25");
}

</style>
