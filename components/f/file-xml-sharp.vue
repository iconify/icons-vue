<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rh2140hgr"/><path class="stlcgs8pw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-xml-sharp" /></template>
<style>
.rh2140hgr {
  d: path("M13.75 2.75h-9v18.5h14.5v-13Z");
}

.stlcgs8pw {
  d: path("M13.75 2.75v5.5h5.5M9.75 12l-2 2.5l2 2.5m4.5-5l2 2.5l-2 2.5m-1.5-5.5l-1.5 6");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
