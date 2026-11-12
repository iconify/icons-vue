<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d7uop2bia"/><path class="hssqz14fh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:boolean-exclude-duotone-sharp" /></template>
<style>
.d7uop2bia {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 2a1 1 0 0 1 1 1v5h5a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1v-5H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm-1 8h-4v4h4Z");
}

.ft5dv1b6b {
  fill: none;
}

.hssqz14fh {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h12v6H9v6H3zm12 6h6v12H9v-6h6z");
}

</style>
