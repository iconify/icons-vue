<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gbf_r6moz"/><path class="mehks01rk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:handbag-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gbf_r6moz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 8h8c1.396 0 2.651 1.256 3 3l1 5c.414 2.069-1.034 4-3 4H7c-1.966 0-3.414-1.931-3-4l1-5c.349-1.744 1.604-3 3-3");
}

.mehks01rk {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 8h4c1.395 0 2.651 1.256 3 3l1 5c.414 2.07-1.034 4-3 4H7c-1.966 0-3.414-1.93-3-4l1-5c.349-1.744 1.604-3 3-3zM8 8a4 4 0 1 1 8 0");
}

</style>
