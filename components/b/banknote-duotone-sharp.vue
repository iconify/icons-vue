<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lxv1x0bmd"/><path class="u4906ybbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:banknote-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lxv1x0bmd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 6v12H3V6Zm-9 8a2 2 0 1 0 .001-3.999A2 2 0 0 0 12 14");
}

.u4906ybbk {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6h18v12H3Zm7 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-3 0h.01M17 12h.01");
}

</style>
