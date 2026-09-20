<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e6h0tjbiq"/><path class="aho1hjbgy"/><path class="qcyhweblp"/><path class="p-qzc1t-u"/><path class="uih_zvhtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:heatwave-outline-regular" /></template>
<style>
.aho1hjbgy {
  d: path("M5 8h2.5");
}

.e6h0tjbiq {
  d: path("M8 8a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p-qzc1t-u {
  d: path("M4 16h8a3 3 0 1 1 -3 3");
}

.qcyhweblp {
  d: path("M16.5 8H19");
}

.uih_zvhtv {
  d: path("M4 21h16");
}

</style>
