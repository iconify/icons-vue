<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rnzxhib7j"/><path class="dz5mbh6ga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-minus-duotone" /></template>
<style>
.dz5mbh6ga {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m17 17l-4 4a1.414 1.414 0 0 1-2 0l-8-8a1.414 1.414 0 0 1 0-2l8-8a1.414 1.414 0 0 1 2 0l8 8a1.414 1.414 0 0 1 0 2zm-8-5h6");
}

.ft5dv1b6b {
  fill: none;
}

.rnzxhib7j {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m17 17l-4 4a1.415 1.415 0 0 1-2 0l-8-8a1.415 1.415 0 0 1 0-2l8-8a1.415 1.415 0 0 1 2 0l8 8a1.415 1.415 0 0 1 0 2Z");
}

</style>
