<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gi03txbct"/><path class="e_21aj3lm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:first-aid-duotone-sharp" /></template>
<style>
.e_21aj3lm {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 3h6v6h6v6h-6v6H9v-6H3V9h6z");
}

.ft5dv1b6b {
  fill: none;
}

.gi03txbct {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 3v6h6v6h-6v6H9v-6H3V9h6V3Z");
}

</style>
