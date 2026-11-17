<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i2fvgcbrl"/><path class="ck__7cbcg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-4-duotone" /></template>
<style>
.ck__7cbcg {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3 11l7.671-6.819a2 2 0 0 1 2.658 0L21 11m-2-1.778V19a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V9.222M12 17h-2a1 1 0 0 1-1-1v-3.884a1 1 0 0 1 .336-.748l2-1.777a1 1 0 0 1 1.328 0l2 1.777a1 1 0 0 1 .336.748V16a1 1 0 0 1-1 1z");
}

.ft5dv1b6b {
  fill: none;
}

.i2fvgcbrl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m21 11l-.013.015L19 9.249V19a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V9.249l-1.987 1.766L3 11l7.671-6.819a2 2 0 0 1 2.658 0Z");
}

</style>
