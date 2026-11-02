<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="iffzk3bmu"/><path class="i_vvj88ui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:column-plus-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i_vvj88ui {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 7a3 3 0 0 1 6 0v10a3 3 0 0 1-6 0Zm10 5h6m-3-3v6");
}

.iffzk3bmu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 7a3 3 0 1 1 6 0v10a3 3 0 1 1-6 0Z");
}

</style>
