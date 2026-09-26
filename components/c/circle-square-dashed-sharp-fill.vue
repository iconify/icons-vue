<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="btg_g3a2s"/><path class="ai_ipiowx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-square-dashed-sharp-fill" /></template>
<style>
.ai_ipiowx {
  d: path("M19 9L22 9L22 12M22 14L22 17M22 19L22 22L19 22M17 22L14 22M12 22L9 22L9 19");
}

.btg_g3a2s {
  fill: currentColor;
  d: path("M17 9C17 13.2803 13.2803 17 9 17C4.7197 17 1 13.2803 1 9C1 4.7197 4.7197 1 9 1C13.2803 1 17 4.7197 17 9Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
