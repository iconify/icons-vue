<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c3n13ibyi"/><path class="h--2zto-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-area-duotone-round" /></template>
<style>
.c3n13ibyi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 13c0-.763.48-1.479 1-2l1-1a1.415 1.415 0 0 1 2 0l1 1a1.415 1.415 0 0 0 2 0l4-4c.369-.369 1 .262 1 1v6a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2Z");
}

.ft5dv1b6b {
  fill: none;
}

.h--2zto-i {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 14v-1c0-.64.36-1.36 1-2l1-1a1.414 1.414 0 0 1 2 0l1 1a1.414 1.414 0 0 0 2 0l4-4c.369-.369 1 .262 1 1v6a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2M3 4v12a4 4 0 0 0 4 4h14");
}

</style>
