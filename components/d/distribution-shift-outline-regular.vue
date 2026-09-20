<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mddrthmzf"/><path class="xa0iemevq"/><path class="e9i5dwbzy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:distribution-shift-outline-regular" /></template>
<style>
.e9i5dwbzy {
  d: path("m10.5 13.5 3 -3");
}

.mddrthmzf {
  d: path("M3 16a4 4 0 0 1 8 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xa0iemevq {
  d: path("M13 12a4 4 0 0 1 8 0");
}

</style>
