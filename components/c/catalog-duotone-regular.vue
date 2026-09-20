<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eqlzrbbhn"/><path class="e0ny3obuy"/><path class="dat-xhb8u"/><path class="iwoy52b7h"/><path class="um6qav7po"/><path class="xbz5-ab-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:catalog-duotone-regular" /></template>
<style>
.dat-xhb8u {
  fill: currentColor;
  d: path("M11.5 11a2 2 0 0 1 2 -2H16a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2h-2.5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.e0ny3obuy {
  fill: currentColor;
  d: path("M2 11a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.eqlzrbbhn {
  fill: currentColor;
  d: path("M3 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.iwoy52b7h {
  d: path("M3 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.um6qav7po {
  d: path("M2 11a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.xbz5-ab-d {
  d: path("M11.5 11a2 2 0 0 1 2 -2H16a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2h-2.5a2 2 0 0 1 -2 -2Z");
}

</style>
