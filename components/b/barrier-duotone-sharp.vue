<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kz39urgyr"/><path class="ydv2bcbpe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:barrier-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kz39urgyr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 7h18v6H3Z");
}

.ydv2bcbpe {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7h18v6H3zm2 6v5m14-5v5M3 18h4m10 0h4M3 7l6 6m0-6l6 6m0-6l6 6");
}

</style>
