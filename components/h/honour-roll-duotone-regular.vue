<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ttrxo2bov"/><path class="jqxl7db2x"/><path class="tu0fdo1xi"/><path class="uepsd3bvn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:honour-roll-duotone-regular" /></template>
<style>
.jqxl7db2x {
  d: path("M4 3h16v17l-8 -8 -8 8Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ttrxo2bov {
  fill: currentColor;
  d: path("M4 3h16v17l-8 -8 -8 8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.tu0fdo1xi {
  d: path("M7 7h10");
}

.uepsd3bvn {
  d: path("M7 10h7");
}

</style>
