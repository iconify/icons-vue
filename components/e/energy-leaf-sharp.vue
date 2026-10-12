<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qrwe3ybjs"/><path class="pzy_hyb8w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:energy-leaf-sharp" /></template>
<style>
.pzy_hyb8w {
  d: path("M16.75 8.25C17 4.93 18 3.25 21.25 3C21 6.32 20 8 16.75 8.25Z");
}

.qrwe3ybjs {
  d: path("M8 7.5h9.5V12l-.99 1.13l-1.52 1.74L14 16h-4l-.99-1.13l-1.52-1.74L6.5 12V7.5zm1.5 0V3m4 4.5V3M12 16v5.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
