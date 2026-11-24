<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w8xb2pb5x"/><path class="swcgs7b8k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-plus-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.swcgs7b8k {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 5H5v16h4M19 9V5h-4M9 5V3h6v2M9 5v2h6V5m-2 12h8m-4-4v8");
}

.w8xb2pb5x {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 5v4H9v12H5V5Z");
}

</style>
