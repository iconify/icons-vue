<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rh2140hgr"/><path class="stubvwbgm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-database-sharp" /></template>
<style>
.rh2140hgr {
  d: path("M13.75 2.75h-9v18.5h14.5v-13Z");
}

.stubvwbgm {
  d: path("M13.75 2.75v5.5h5.5m-10.5 3.5c0-.83 1.46-1.5 3.25-1.5s3.25.67 3.25 1.5v5.5c0 .83-1.46 1.5-3.25 1.5s-3.25-.67-3.25-1.5Zm0 0c0 .83 1.46 1.5 3.25 1.5s3.25-.67 3.25-1.5m-6.5 2.75c0 .83 1.46 1.5 3.25 1.5s3.25-.67 3.25-1.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
