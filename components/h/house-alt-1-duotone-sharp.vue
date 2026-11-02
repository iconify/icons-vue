<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cxdr51b1v"/><path class="vg804qpvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-1-duotone-sharp" /></template>
<style>
.cxdr51b1v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 17v4a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V11c0-.265.105-.52.293-.707l8-8a1 1 0 0 1 1.414 0l8 8A1 1 0 0 1 21 11v10a1 1 0 0 1-1 1h-6a1 1 0 0 1-1-1v-4a1 1 0 0 0-2 0");
}

.ft5dv1b6b {
  fill: none;
}

.vg804qpvz {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 17v4h6V11l-8-8l-8 8v10h6v-4a2 2 0 1 1 4 0");
}

</style>
