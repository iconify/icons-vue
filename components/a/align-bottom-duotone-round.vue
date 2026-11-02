<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l3xgu4b8f"/><path class="urx1dyvef"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-bottom-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l3xgu4b8f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 7a3 3 0 1 1 6 0v6a3 3 0 1 1-6 0Zm10 4a3 3 0 1 1 6 0v2a3 3 0 1 1-6 0Z");
}

.urx1dyvef {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 4a3 3 0 0 0-3 3v6a3 3 0 0 0 6 0V7a3 3 0 0 0-3-3m10 4a3 3 0 0 0-3 3v2a3 3 0 0 0 6 0v-2a3 3 0 0 0-3-3M3 20h18");
}

</style>
