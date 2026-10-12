<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kd-mli2zy"/><path class="m8mi84byg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-left-right-two-tone" /></template>
<style>
.kd-mli2zy {
  stroke-opacity: 0.4;
  d: path("M21 7L3 7M7 11L3 7L7 3");
}

.m8mi84byg {
  d: path("M3 17L21 17M17 13L21 17L17 21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
