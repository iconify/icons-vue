<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="l047723yv"/><path class="w-wwzbctp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cardigan-sharp" /></template>
<style>
.l047723yv {
  d: path("M9.75 4.5h5.75l1.1.58l2.05 1.09l1.1.58l.15 1.24l1.2 9.77l.15 1.24l-1.22.26l-1.06.23q-1.22.26-2.47.26h-9q-1.25 0-2.47-.26l-1.06-.23L2.75 19l.15-1.24l1.2-9.77l.15-1.24l1.1-.58L7.4 5.08l1.1-.58z");
}

.w-wwzbctp {
  d: path("M9.25 4.75L12 13.5v6.25m2.75-15L12 13.5m-6.5 3.75v2.25m3.25-2.25v2.5m6.5-2.5v2.5m3.25-2.5v2.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
