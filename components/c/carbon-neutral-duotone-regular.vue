<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ubad4_0-e"/><path class="e3ejqd_wm"/><path class="qp4c7tbym"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:carbon-neutral-duotone-regular" /></template>
<style>
.e3ejqd_wm {
  d: path("M5 15a4 4 0 0 1 2 -7 5 5 0 0 1 9 -1 4.5 4.5 0 0 1 3 8Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qp4c7tbym {
  d: path("m8 18 3 3 5 -5");
}

.ubad4_0-e {
  fill: currentColor;
  d: path("M5 15a4 4 0 0 1 2 -7 5 5 0 0 1 9 -1 4.5 4.5 0 0 1 3 8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
