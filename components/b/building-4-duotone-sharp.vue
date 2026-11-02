<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="is2ug93pg"/><path class="ni3qzbr4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-4-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.is2ug93pg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 4a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Zm5 5h2a1 1 0 0 0 0-2H9a1 1 0 0 0 0 2m0 4h2a1 1 0 0 0 0-2H9a1 1 0 0 0 0 2");
}

.ni3qzbr4i {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 20h18M5 20V4h10v16m0-11h4v11M9 8h2m-2 4h2");
}

</style>
