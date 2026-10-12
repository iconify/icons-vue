<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="h5bs-jn_e"/><path class="p0kifjbvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:brake-caliper-sharp" /></template>
<style>
.h5bs-jn_e {
  cx: 11px;
  cy: 13px;
  r: 7.75px;
}

.p0kifjbvl {
  d: path("M11 10.5a2.5 2.5 0 1 0 0 5a2.5 2.5 0 0 0 0-5Zm1.78-7.59a10.25 10.25 0 0 1 8.31 8.31l-4.92.87a5.25 5.25 0 0 0-4.26-4.26Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
