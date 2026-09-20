<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ns27x6b-j"/><path class="xvse_9aut"/><path class="kjs-2gbxx"/><path class="cvlyf4b3z"/><path class="ryja2j08k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:elderly-duotone-regular" /></template>
<style>
.cvlyf4b3z {
  d: path("m4 20 5 -5 5 5");
}

.kjs-2gbxx {
  d: path("M9 8v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ns27x6b-j {
  fill: currentColor;
  d: path("M6 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ryja2j08k {
  d: path("M18 20V9a2 2 0 0 0 -4 0");
}

.xvse_9aut {
  d: path("M6 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
