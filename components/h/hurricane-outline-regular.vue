<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bo51iypxr"/><path class="tp8vjxbvr"/><path class="cvdxfrhpf"/><path class="razwus2gf"/><path class="b_28-wbex"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hurricane-outline-regular" /></template>
<style>
.b_28-wbex {
  d: path("M6 12v8h7");
}

.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.cvdxfrhpf {
  d: path("M18 12a6 6 0 0 1 -12 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.razwus2gf {
  d: path("M18 12V4h-7");
}

.tp8vjxbvr {
  d: path("M6 12a6 6 0 0 1 12 0");
}

</style>
