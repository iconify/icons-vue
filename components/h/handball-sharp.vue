<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="igrl4dbev"/><circle class="djkwb3blv"/><path class="opfpp_bly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:handball-sharp" /></template>
<style>
.djkwb3blv {
  cx: 18px;
  cy: 4.75px;
  r: 1.75px;
}

.igrl4dbev {
  cx: 10.75px;
  cy: 6px;
  r: 1.75px;
}

.opfpp_bly {
  d: path("M11.25 9.25L10 14.5m1.25-5.25l4.5-3m-4.5 3L7.5 11.5l-2-1.75M10 14.5l3.5 2.5l-1 4.25M10 14.5l-3.5 2L5 20.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
