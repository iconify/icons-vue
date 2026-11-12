<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="oinufb20v"/><path class="luywdci8b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-clock-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.luywdci8b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6h9v2M8 20H3V4h7l2 2m0 11a5 5 0 1 0 10 0a5 5 0 0 0-10 0m5-2v2h2");
}

.oinufb20v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 3c.265 0 .52.105.707.293L12.414 5H21a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H9v11a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1Z");
}

</style>
