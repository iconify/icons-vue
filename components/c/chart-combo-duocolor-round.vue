<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k9m2c6bjq"/><path class="fi2r0pf6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-combo-duocolor-round" /></template>
<style>
.fi2r0pf6n {
  d: path("M7 16v4m6-6v6m6-8v8M3 4v12a4 4 0 0 0 4 4h14");
}

.k9m2c6bjq {
  stroke-opacity: 0.4;
  d: path("m3 11l4-4c1.163-1.163 3.256-1.163 5 0s3.837 1.163 5 0l4-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
