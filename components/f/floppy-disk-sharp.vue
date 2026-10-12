<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nlzriacro"/><path class="qjm2jz-od"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:floppy-disk-sharp" /></template>
<style>
.nlzriacro {
  d: path("m2.75 7.4l.012-.824L3.35 6L6 3.35l.576-.588l.824-.012h13.85v18.5H2.75v-2.5Z");
}

.qjm2jz-od {
  d: path("M8.75 5h8.5v5.25h-8.5zm5.75 1.5v2.25m-7.75 5.5h10.5m-10.5 3h10.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
