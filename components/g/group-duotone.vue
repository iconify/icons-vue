<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lznw0br_t"/><path class="lwdlm50ru"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:group-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lwdlm50ru {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 12H8a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1h5a1 1 0 0 1 1 1zm-4 0h6a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1h-5a1 1 0 0 1-1-1zM3 6V5a2 2 0 0 1 2-2h1m12 0h1a2 2 0 0 1 2 2v1m0 12v1a2 2 0 0 1-2 2h-1M6 21H5a2 2 0 0 1-2-2v-1");
}

.lznw0br_t {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 11a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2h-5a2 2 0 0 1-2-2v-4a1 1 0 0 1 1-1Z");
}

</style>
