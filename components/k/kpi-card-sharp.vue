<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="secm0bcqr"/><path class="cc_0sbb0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kpi-card-sharp" /></template>
<style>
.cc_0sbb0p {
  d: path("M6.5 11h7v5h-7zm9.5 4.5l1.75-2l1.75 2");
}

.secm0bcqr {
  d: path("M2.75 3.75h18.5v16.5H2.75zM6.5 8h5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
