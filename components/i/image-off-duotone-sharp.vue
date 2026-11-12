<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wwc122nnc"/><path class="ropczjbno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-off-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ropczjbno {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 3h12v12m0 6H3V3m0 14l7-7m6-3a1 1 0 1 0 2 0a1 1 0 0 0-2 0M2 2l20 20");
}

.wwc122nnc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 21H3V3ZM9 3h12v12Z");
}

</style>
