<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hzjmt33wk"/><path class="vjreofyjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-minus-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hzjmt33wk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 5h14v16H5Z");
}

.vjreofyjs {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 5H5v16h14V5h-4M9 5V3h6v2M9 5v2h6V5m-6 9h6");
}

</style>
