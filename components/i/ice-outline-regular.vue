<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="plts5tbsc"/><path class="e70mzkkad"/><path class="ricsl-blc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ice-outline-regular" /></template>
<style>
.e70mzkkad {
  d: path("m6 9 3 3h6l3 -3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.plts5tbsc {
  d: path("M6 4h12v11l-6 6 -6 -6Z");
}

.ricsl-blc {
  d: path("M12 12v9");
}

</style>
