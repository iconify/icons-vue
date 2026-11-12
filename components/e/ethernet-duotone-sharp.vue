<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u62ba8bsz"/><path class="m238sjb2g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ethernet-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m238sjb2g {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 4h18v13h-4v4H7v-4H3zm3 4v3m4-3v3m4-3v3m4-3v3");
}

.u62ba8bsz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 4v13h-4v4H7v-4H3V4Z");
}

</style>
