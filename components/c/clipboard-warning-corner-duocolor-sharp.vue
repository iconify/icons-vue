<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e906b4bdd"/><path class="l9hk-5x4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-warning-corner-duocolor-sharp" /></template>
<style>
.e906b4bdd {
  stroke-opacity: 0.4;
  d: path("M17 14v4m0 3h.01");
}

.l9hk-5x4f {
  d: path("M9 5H5v16h4M19 9V5h-4M9 5V3h6v2M9 5v2h6V5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
