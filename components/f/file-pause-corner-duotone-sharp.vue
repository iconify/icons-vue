<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qm_sx7_ee"/><path class="sbppgebog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-pause-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.qm_sx7_ee {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 10h-9v11a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1h8c.265 0 .52.105.707.293l6 6A1 1 0 0 1 19 10m-6-2h4l-4-4Z");
}

.sbppgebog {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H5v18h4m4-18l6 6m-6-6v6h6m-4 4v8m4-8v8");
}

</style>
