<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pmxfg0buc"/><path class="bll58zlnb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bookmark-off-duotone-sharp" /></template>
<style>
.bll58zlnb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 4h6v7m0 6v3l-6-4l-6 4V5M3 2l19 19");
}

.ft5dv1b6b {
  fill: none;
}

.pmxfg0buc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18 3a1 1 0 0 1 1 1v16a1 1 0 0 1-1.555.832L12 17.202l-5.445 3.63A1 1 0 0 1 5 20V4a1 1 0 0 1 1-1Z");
}

</style>
