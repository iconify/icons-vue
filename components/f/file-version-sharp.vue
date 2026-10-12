<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="a2lxl3bwz"/><path class="i9edhf24b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-version-sharp" /></template>
<style>
.a2lxl3bwz {
  d: path("M15.75 3.75h-7.5v17.5h12.5V8.75Z");
}

.i9edhf24b {
  d: path("M15.75 3.75v5h5M5.25 6v13M2.75 8.25v8.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
