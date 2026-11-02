<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w043ls85r"/><path class="flbrdsbsk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cast-duotone-round" /></template>
<style>
.flbrdsbsk {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7a2 2 0 0 1 2-2h12a4 4 0 0 1 4 4v6a4 4 0 0 1-4 4h-2M3 11a8 8 0 0 1 8 8m-8-4a4 4 0 0 1 4 4m-4 0h.01");
}

.ft5dv1b6b {
  fill: none;
}

.w043ls85r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 5h5a4 4 0 0 1 4 4v6a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4V7a2 2 0 0 1 2-2Z");
}

</style>
