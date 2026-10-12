<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="na1joymnn"/><path class="uahb6znqr"/><path class="nk-di3bjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:halloween-pumpkin-sharp" /></template>
<style>
.na1joymnn {
  d: path("M12 6.25V3.5l2.25-.75");
}

.nk-di3bjz {
  d: path("M7.25 12.25L8.75 10l1.5 2.25Zm6.5 0l1.5-2.25l1.5 2.25ZM7 15.5l1.6 1.6l1.6-1.35L12 17.1l1.8-1.35l1.6 1.35l1.6-1.6");
}

.uahb6znqr {
  d: path("m12 6.5l-1.25-.75h-2C5.25 5.75 3 9.25 3 13.5s2.25 7.75 5.75 7.75h1.583l1.667-1l1.667 1h1.583c3.5 0 5.75-3.5 5.75-7.75s-2.25-7.75-5.75-7.75h-2z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
