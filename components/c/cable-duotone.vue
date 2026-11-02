<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lk1166vkd"/><path class="vgsharbux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cable-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lk1166vkd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 4h4a3 3 0 1 1 0 6H5a3 3 0 1 1 0-6m10 10h4a3 3 0 1 1 0 6h-4a3 3 0 1 1 0-6");
}

.vgsharbux {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7a2 2 0 0 1 2-2h4a2 2 0 1 1 0 4H5a2 2 0 0 1-2-2m10 10a2 2 0 0 1 2-2h4a2 2 0 1 1 0 4h-4a2 2 0 0 1-2-2M5 3v2m4-2v2m6 14v2m4-2v2M7 9v1a2 2 0 0 0 2 2h6a2 2 0 0 1 2 2v1");
}

</style>
