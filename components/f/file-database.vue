<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jz9wy2bsc"/><path class="m3bft0bvt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-database" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jz9wy2bsc {
  d: path("M13.75 2.75h-6.5a2.5 2.5 0 0 0-2.5 2.5v13.5a2.5 2.5 0 0 0 2.5 2.5h9.5a2.5 2.5 0 0 0 2.5-2.5V8.25Z");
}

.m3bft0bvt {
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5m-10.5 3.5c0-.83 1.46-1.5 3.25-1.5s3.25.67 3.25 1.5v5.5c0 .83-1.46 1.5-3.25 1.5s-3.25-.67-3.25-1.5Zm0 0c0 .83 1.46 1.5 3.25 1.5s3.25-.67 3.25-1.5m-6.5 2.75c0 .83 1.46 1.5 3.25 1.5s3.25-.67 3.25-1.5");
}

</style>
