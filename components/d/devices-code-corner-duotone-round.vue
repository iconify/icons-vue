<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kbc_4nbnz"/><path class="e7_9r5b7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:devices-code-corner-duotone-round" /></template>
<style>
.e7_9r5b7f {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 6a3 3 0 0 1 6 0v4a3 3 0 0 1-6 0Zm-4-2H7a4 4 0 0 0-4 4v4a4 4 0 0 0 4 4h3m5 1l-2 2l2 2m4-4l2 2l-2 2");
}

.ft5dv1b6b {
  fill: none;
}

.kbc_4nbnz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 6v4a3 3 0 1 1-6 0V6a3 3 0 1 1 6 0");
}

</style>
