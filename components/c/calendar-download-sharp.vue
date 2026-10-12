<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="cctd6fbog"/><path class="xgrkztuqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:calendar-download-sharp" /></template>
<style>
.cctd6fbog {
  d: path("M2.75 4.75h18.5v16.5H2.75zm5.25-2v3.5m8-3.5v3.5M2.75 9.75h18.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xgrkztuqs {
  d: path("M12 18.5c-2.5-1.5-4-3-4-4.6v-1.65h3.125l.875 1.4l.875-1.4H16v1.65c0 1.6-1.5 3.1-4 4.6Z");
}

</style>
