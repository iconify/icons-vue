<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kn0tcm93r"/><path class="ymw3aibdo"/><path class="jg5k_rbda"/><path class="h3f_66bxu"/><path class="i3md2ibef"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gpu-queue-outline-regular" /></template>
<style>
.h3f_66bxu {
  d: path("M14 12h5a3 3 0 0 1 3 3v3a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3v-3l3 -3h5");
}

.i3md2ibef {
  d: path("M5 16.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.jg5k_rbda {
  d: path("M16 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.kn0tcm93r {
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ymw3aibdo {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
