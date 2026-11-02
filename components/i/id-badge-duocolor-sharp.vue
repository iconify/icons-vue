<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ztx3s-f0k"/><path class="r9vsajs-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:id-badge-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r9vsajs-e {
  d: path("M5 3h14v18H5Zm5 3h4");
}

.ztx3s-f0k {
  stroke-opacity: 0.4;
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-1 9a3 3 0 0 1 6 0");
}

</style>
