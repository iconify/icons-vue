<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tt8p8-b4v"/><path class="c41uubbcp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:log-in-duotone-round" /></template>
<style>
.c41uubbcp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 7a4 4 0 0 1 4-4h3a4 4 0 0 1 4 4v10a4 4 0 0 1-4 4h-3a4 4 0 0 1-4-4m4-2l3-3m0 0l-3-3m3 3H5");
}

.ft5dv1b6b {
  fill: none;
}

.tt8p8-b4v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 7a4 4 0 0 1 4-4h3a4 4 0 0 1 4 4v10a4 4 0 0 1-4 4h-3a4 4 0 0 1-4-4Z");
}

</style>
