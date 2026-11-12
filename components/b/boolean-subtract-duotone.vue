<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rpl37cbvz"/><path class="gvyhijbnf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:boolean-subtract-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gvyhijbnf {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 3h5a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-4a1 1 0 0 0-1 1v4a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1zm10 6h1a1 1 0 0 1 1 1v3m0 4v3a1 1 0 0 1-1 1h-3m-8-2v1a1 1 0 0 0 1 1h3");
}

.rpl37cbvz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M14 2a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-4v4a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2Z");
}

</style>
