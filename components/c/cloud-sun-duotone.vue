<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="js4epwk0u"/><path class="wfg-fvvzd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-sun-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.js4epwk0u {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5.667 21a2.668 2.668 0 0 1-2.31-4a2.67 2.67 0 0 1 2.31-1.333C7 11.667 13 12.333 13 17a2 2 0 1 1 0 4Z");
}

.wfg-fvvzd {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.667 21a2.667 2.667 0 0 1 0-5.333C7 11.667 13 12.333 13 17a2 2 0 1 1 0 4Zm5.258-11.8a3 3 0 0 1 4.03 2.28M19 12h2M7.05 7.05L5.636 5.636M12 5V3m4.95 4.05l1.414-1.414");
}

</style>
