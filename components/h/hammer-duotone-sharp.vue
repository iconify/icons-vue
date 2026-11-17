<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t54cukbni"/><path class="tprfi6wge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hammer-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.t54cukbni {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 20a2.122 2.122 0 0 1-3-3l8-8V8c-.001-1.52-.964-2.963-2-4L9 3h4c1.52.001 2.963.964 4 2l2 2v2l2 2l-3 3l-2-2h-1Z");
}

.tprfi6wge {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9 3l1 1c1.28 1.28 2 2.72 2 4v2l2 2h2l2 2l3-3l-2-2V7l-2-2c-1.28-1.28-2.72-2-4-2zm6 9l-8 8a2.121 2.121 0 1 1-3-3l8-8");
}

</style>
