<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h_cr2obrq"/><path class="xh69ljbkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bracket-arrow-right-duotone" /></template>
<style>
.h_cr2obrq {
  stroke-opacity: 0.4;
  d: path("M11.1093 4L6 4C3.7909 4 2 5.7909 2 8L2 16C2 18.2091 3.7909 20 6 20L11.1093 20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xh69ljbkl {
  d: path("M21.2307 12L11.1093 12M16.17 6.5L21.8359 11.6314C22.0547 11.8296 22.0547 12.1704 21.8359 12.3686L16.17 17.5");
}

</style>
