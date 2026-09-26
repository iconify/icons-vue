<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jrdz-v_np"/><path class="u-rt09xuf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-up-right-dashed-panel-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jrdz-v_np {
  stroke-opacity: 0.4;
  d: path("M9.5 21L14.5 21M3 14.5L3 9.5M8 3L3 3L3 7M3 17L3 21L7 21M21 16L21 21.0001L17 21");
}

.u-rt09xuf {
  d: path("M10.5 3L21 3L21 13.5M11.2071 12.7929L20.8536 3.1464");
}

</style>
