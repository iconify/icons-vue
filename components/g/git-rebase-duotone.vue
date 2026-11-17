<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kz7-r4hmu"/><path class="gy3rkcb7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-rebase-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gy3rkcb7l {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m0 12a2 2 0 1 0 4 0a2 2 0 0 0-4 0M17 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0M5 8v8M7 6h10m2 15v-6a2 2 0 0 0-2-2h-6m3-3l-3 3l3 3");
}

.kz7-r4hmu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 6a2 2 0 1 1 3.999-.001A2 2 0 0 1 3 6m14 0a2 2 0 1 1 3.999-.001A2 2 0 0 1 17 6M3 18a2 2 0 1 1 3.999-.001A2 2 0 0 1 3 18");
}

</style>
