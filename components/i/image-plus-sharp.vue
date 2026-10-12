<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lz4i0_b0z"/><circle class="p_flhjbml"/><path class="wtv3gaceq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:image-plus-sharp" /></template>
<style>
.lz4i0_b0z {
  d: path("M11.75 20.25h-9V3.75h18.5v8");
}

.p_flhjbml {
  cx: 8.5px;
  cy: 9px;
  r: 1.75px;
}

.wtv3gaceq {
  d: path("m2.75 16.25l4.1-4.1l1.125-1.112L9.1 12.15l3.15 3.15m5.25-.55v5.5m-2.75-2.75h5.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
