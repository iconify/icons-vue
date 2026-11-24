<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xutdsqbpy"/><path class="hldvvhd1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-warning-corner-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hldvvhd1o {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 17c-1.28 0-2.36.36-3 1l-1 1c-.738.738-2-.524-2-2V7a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v2m-4 5v4m0 3h.01");
}

.xutdsqbpy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13 9a4 4 0 0 0-4 4v4c-1.041 0-2.236.237-3 1l-1 1c-.738.738-2-.524-2-2V7a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v2Z");
}

</style>
