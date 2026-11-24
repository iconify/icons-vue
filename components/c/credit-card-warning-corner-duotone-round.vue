<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bsrvo5b0s"/><path class="uplk5nbjt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-warning-corner-duotone-round" /></template>
<style>
.bsrvo5b0s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 5a4 4 0 0 1 4 4H9v10H7a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4Z");
}

.ft5dv1b6b {
  fill: none;
}

.uplk5nbjt {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 9a4 4 0 0 0-4-4H7a4 4 0 0 0-4 4v6a4 4 0 0 0 4 4h2M3 9h18m-4 5v4m0 3h.01");
}

</style>
