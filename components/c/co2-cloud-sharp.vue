<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="v9402bb4w"/><path class="plmtydwed"/><circle class="m0ewde4zh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:co2-cloud-sharp" /></template>
<style>
.m0ewde4zh {
  cx: 13.75px;
  cy: 15.5px;
  r: 1.5px;
}

.plmtydwed {
  d: path("M9.75 14.1a1.75 1.75 0 1 0 0 2.8");
}

.v9402bb4w {
  d: path("M6.75 19.6a4 4 0 0 1-.55-7.96a5.75 5.75 0 0 1 10.65-1.39a4.5 4.5 0 0 1-.6 9.35Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
