<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lv46fdvld"/><path class="z3g4_cbem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-sort-two-tone" /></template>
<style>
.lv46fdvld {
  stroke-opacity: 0.4;
  d: path("M6 10L6 3M3 6L6 3L9 6M6 14L6 21M3 18L6 21L9 18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z3g4_cbem {
  d: path("M13 6L21 6M13 12L21 12M13 18L21 18");
}

</style>
