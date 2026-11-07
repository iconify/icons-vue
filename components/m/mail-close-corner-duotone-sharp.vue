<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mgw_z8cdr"/><path class="uk02l25ja"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-close-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mgw_z8cdr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-9v7a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

.uk02l25ja {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 19H3V5h18v6M3 5l6 6h6l6-6m-5 11l4 4m0-4l-4 4");
}

</style>
