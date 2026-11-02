<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tnyv1z21n"/><path class="khhwrpp4r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-top-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.khhwrpp4r {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 8a3 3 0 0 0-3 3v6a3 3 0 0 0 6 0v-6a3 3 0 0 0-3-3m10 0a3 3 0 0 0-3 3v2a3 3 0 0 0 6 0v-2a3 3 0 0 0-3-3M3 4h18");
}

.tnyv1z21n {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 11a3 3 0 1 1 6 0v6a3 3 0 1 1-6 0Zm10 0a3 3 0 1 1 6 0v2a3 3 0 1 1-6 0Z");
}

</style>
