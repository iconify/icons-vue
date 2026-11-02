<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bc6ox0x8m"/><path class="cgq798g2j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heart-alt-duotone" /></template>
<style>
.bc6ox0x8m {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13 6a4.242 4.242 0 1 1 6 6l-6 6a1.415 1.415 0 0 1-2 0l-6-6a4.242 4.242 0 1 1 6-6l1 1Z");
}

.cgq798g2j {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 7l1-1a4.243 4.243 0 0 1 6 6l-6 6a1.414 1.414 0 0 1-2 0l-6-6a4.243 4.243 0 0 1 6-6z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
