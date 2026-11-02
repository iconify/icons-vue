<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vhvibju4r"/><path class="whu995bxg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bus-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.vhvibju4r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 17a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V7a5 5 0 0 1 5-5h6a5 5 0 0 1 5 5Z");
}

.whu995bxg {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 11v6a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V7a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4zM7 19h2v2H7Zm8 0h2v2h-2ZM5 13h14M9 6h6M8 16h.01M16 16h.01");
}

</style>
