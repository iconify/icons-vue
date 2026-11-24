<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fy3l66bie"/><path class="izb-0ij3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-apartment-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fy3l66bie {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 21V6a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v15Z");
}

.izb-0ij3i {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 21h18M7 21V6a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v15M10 8h.01M14 8h.01M10 12h.01M14 12h.01M10 21v-2a2 2 0 1 1 4 0v2M7 11H5a2 2 0 0 0-2 2v8m14-10h2a2 2 0 0 1 2 2v8");
}

</style>
