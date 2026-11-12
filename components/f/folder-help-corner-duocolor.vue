<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zdt5grb0s"/><path class="glkq_3w0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-help-corner-duocolor" /></template>
<style>
.glkq_3w0k {
  d: path("M12 6h7a2 2 0 0 1 2 2M8 20H5a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h5l2 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zdt5grb0s {
  stroke-opacity: 0.4;
  d: path("M15 16a2 2 0 1 1 2 2m0 3h.01");
}

</style>
