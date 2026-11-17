<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fax9lzbfg"/><path class="n43s3iyqb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fox-duotone-sharp" /></template>
<style>
.fax9lzbfg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m14 8l5-5v7l1 3l-8 8l-8-8l1-3V3l5 5Z");
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
