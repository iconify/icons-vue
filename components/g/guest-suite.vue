<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h50zkmbpu"/><path class="pesa53gwo"/><path class="ax93j3bfd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:guest-suite" /></template>
<style>
.ax93j3bfd {
  d: path("M13 13.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm0 3.5h2");
}

.h50zkmbpu {
  d: path("M6 21.5V4a1.5 1.5 0 0 1 1.5-1.5h9A1.5 1.5 0 0 1 18 4v17.5m-15.5 0h19");
}

.pesa53gwo {
  d: path("M11.75 11.5h4.5v8h-4.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
