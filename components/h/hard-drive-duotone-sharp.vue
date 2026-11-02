<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wn598tbvx"/><path class="tstsy3b5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hard-drive-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.tstsy3b5j {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3 13l4-8h10l4 8v6H3zm0 0h18M7 16h.01M11 16h.01");
}

.wn598tbvx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 13a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Zm4 3a1 1 0 1 0 2 0a1 1 0 0 0-2 0m4 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
