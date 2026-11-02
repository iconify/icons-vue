<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="sedmwuddk"/><path class="d21zkk1sr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-ethereum-duotone-round" /></template>
<style>
.d21zkk1sr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 3l6 9l-6 9l-6-9zm-6 9l6 3l6-3");
}

.ft5dv1b6b {
  fill: none;
}

.sedmwuddk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m12 3l6 9l-6 9l-6-9Z");
}

</style>
