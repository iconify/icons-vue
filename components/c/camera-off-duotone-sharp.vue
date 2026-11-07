<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wu2n13wsg"/><path class="l42tb2t-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:camera-off-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l42tb2t-x {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 20H3V7h3m4-3zh4l3 3h4v9M9.879 10.879a3 3 0 0 0 4.243 4.243M2 3l19 19");
}

.wu2n13wsg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 16L9.5 4.5L10 4h4l3 3h4Zm-2 4H3V7h3Z");
}

</style>
