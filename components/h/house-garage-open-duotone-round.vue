<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dd-4m6_mz"/><path class="af7zyybzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-garage-open-duotone-round" /></template>
<style>
.af7zyybzg {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 13h2a2 2 0 0 1 2 2v4a2 2 0 1 0 4 0v-7.185a4 4 0 0 0-1.366-3.01l-4-3.5a4 4 0 0 0-5.268 0l-4 3.5A4 4 0 0 0 4 11.815V19a2 2 0 1 0 4 0v-4a2 2 0 0 1 2-2z");
}

.dd-4m6_mz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M14 13h-4a2 2 0 0 0-2 2v4a2 2 0 1 1-4 0v-7.185a4 4 0 0 1 1.366-3.01l4-3.5a4 4 0 0 1 5.268 0l4 3.5A4 4 0 0 1 20 11.815V19a2 2 0 1 1-4 0v-4a2 2 0 0 0-2-2");
}

.ft5dv1b6b {
  fill: none;
}

</style>
