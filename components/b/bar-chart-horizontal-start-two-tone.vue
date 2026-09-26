<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="byaevlepd"/><path class="x-y_kqbjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bar-chart-horizontal-start-two-tone" /></template>
<style>
.byaevlepd {
  stroke-opacity: 0.4;
  d: path("M2 12L22 12M2 20L15 20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x-y_kqbjs {
  d: path("M2 4L8 4");
}

</style>
