<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i5ypyoehl"/><path class="l12_cmb5r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bar-chart-horizontal-end-duotone" /></template>
<style>
.i5ypyoehl {
  stroke-opacity: 0.4;
  d: path("M2 12L22 12M9 20L22 20");
}

.l12_cmb5r {
  d: path("M16 4L22 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
