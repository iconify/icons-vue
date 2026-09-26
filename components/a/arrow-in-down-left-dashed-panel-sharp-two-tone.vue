<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jrdz-v_np"/><path class="dym86ebju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-in-down-left-dashed-panel-sharp-two-tone" /></template>
<style>
.dym86ebju {
  d: path("M11.5 2L11.5 12.5L22 12.5M11.6464 12.3536L21.2929 2.7071");
}

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

</style>
