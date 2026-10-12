<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rh2140hgr"/><path class="d7wr_9bnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-split-sharp" /></template>
<style>
.d7wr_9bnc {
  d: path("M13.75 2.75v5.5h5.5M12 10v1.25c0 2-2.75 2-2.75 4v3.25M12 11.25c0 2 2.75 2 2.75 4v3.25M8 17.25l1.25 1.25l1.25-1.25m3 0l1.25 1.25L16 17.25");
}

.rh2140hgr {
  d: path("M13.75 2.75h-9v18.5h14.5v-13Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
