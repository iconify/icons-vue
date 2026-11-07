<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="eqljr_38w"/><path class="lowt7-bvg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bell-off-duotone-round" /></template>
<style>
.eqljr_38w {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10.227 3.227A7 7 0 0 1 19 10v2ZM15 17v1a3 3 0 1 1-6 0v-1H6a2.003 2.003 0 0 1-2-2c0-1 1-1 1-2v-3a6.98 6.98 0 0 1 1.575-4.425L18 17Z");
}

.ft5dv1b6b {
  fill: none;
}

.lowt7-bvg {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17H6a2 2 0 0 1-2-2c0-1 1-1 1-2v-3c0-1.678.59-3.219 1.575-4.425m3.652-2.348A7 7 0 0 1 19 10v2m-1 5h-6m-3 0v1a3 3 0 0 0 6 0v-1M3 2l19 19");
}

</style>
