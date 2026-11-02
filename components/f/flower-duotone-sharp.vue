<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xnmznwc6q"/><path class="zb4ayzb_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flower-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.xnmznwc6q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 6a3 3 0 1 1 0 6a3 3 0 1 1-6 0a3 3 0 1 1 0-6a3 3 0 1 1 6 0");
}

.zb4ayzb_o {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 6a3 3 0 0 1 6 0a3 3 0 0 1 0 6a3 3 0 0 1-6 0a3 3 0 0 1 0-6m3 9v6m0-12h.01");
}

</style>
