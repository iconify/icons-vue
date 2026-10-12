<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mh6m3mtvi"/><path class="p8x7c0bup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dock-door-sharp" /></template>
<style>
.mh6m3mtvi {
  d: path("M2.75 21.25V2.75h18.5v18.5");
}

.p8x7c0bup {
  d: path("M5.75 5.75h12.5v7.5H5.75zm0 2.5h12.5m-12.5 2.5h12.5m-9 6h5.5v4.5h-5.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
