<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rh2140hgr"/><path class="tdo_q06ah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-pdf-sharp" /></template>
<style>
.rh2140hgr {
  d: path("M13.75 2.75h-9v18.5h14.5v-13Z");
}

.tdo_q06ah {
  d: path("M13.75 2.75v5.5h5.5m-9.25 10v-7.5h2.5a2.25 2.25 0 0 1 0 4.5H10");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
