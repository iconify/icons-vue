<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dxsxh5xhc"/><path class="ezhshdb4i"/><path class="vcy8uoxzr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:courier-app" /></template>
<style>
.dxsxh5xhc {
  d: path("M6 2.5h12v19H6Z");
}

.ezhshdb4i {
  d: path("m12 7l3.25 1.75V13L12 14.75L8.75 13V8.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vcy8uoxzr {
  d: path("M8.75 8.75L12 10.5l3.25-1.75M12 10.5v4.25m-1.5 3.75h3");
}

</style>
