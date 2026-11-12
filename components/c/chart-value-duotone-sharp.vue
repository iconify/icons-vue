<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q-vq7u6zb"/><path class="wf2cz2zvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-value-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.q-vq7u6zb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 5h18v14H3Z");
}

.wf2cz2zvm {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 5h18v14H3Zm3 6l2-2v6m6-6h4v4m0-4l-6 6");
}

</style>
