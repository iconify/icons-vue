<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ugdbidcqi"/><path class="ajxlkdb4q"/><path class="sqmmri1vo"/><path class="da_3coiun"/><path class="vz97hm34i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:data-residency-eu-outline-regular" /></template>
<style>
.ajxlkdb4q {
  d: path("M11 7.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.da_3coiun {
  d: path("M11 16.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sqmmri1vo {
  d: path("M15.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ugdbidcqi {
  d: path("M16.23 2.94a10 10 0 1 1 -8.46 0");
}

.vz97hm34i {
  d: path("M6.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
