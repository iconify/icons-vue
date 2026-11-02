<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="epasj2z1c"/><path class="n43s3iyqb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fox-duotone-sharp" /></template>
<style>
.epasj2z1c {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m13.586 7l4.707-4.707A1 1 0 0 1 20 3v6.838l.949 2.846c.119.359.026.755-.242 1.023l-8 8a1 1 0 0 1-1.414 0l-8-8a1 1 0 0 1-.242-1.023L4 9.838V3a1.002 1.002 0 0 1 1.707-.707L10.414 7Z");
}

.ft5dv1b6b {
  fill: none;
}

.n43s3iyqb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m14 8l5-5v7l1 3l-8 8l-8-8l1-3V3l5 5zm-5 4l1 1m5-1l-1 1m-2 3h.01");
}

</style>
