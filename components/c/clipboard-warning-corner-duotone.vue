<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ayx4qmvds"/><path class="m0fq-41tc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-warning-corner-duotone" /></template>
<style>
.ayx4qmvds {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 9a2 2 0 0 0-2 2v10H7a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v2Z");
}

.ft5dv1b6b {
  fill: none;
}

.m0fq-41tc {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 5H7a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h2M19 9V7a2 2 0 0 0-2-2h-2M9 5V4a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v1M9 5v1a1 1 0 0 0 1 1h4a1 1 0 0 0 1-1V5m2 9v4m0 3h.01");
}

</style>
