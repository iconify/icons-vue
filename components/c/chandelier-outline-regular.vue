<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fnf6pdbdu"/><path class="prhskmb-v"/><path class="ofbkge5tm"/><path class="j7bay-umk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chandelier-outline-regular" /></template>
<style>
.fnf6pdbdu {
  d: path("M12 3v6");
}

.j7bay-umk {
  d: path("M18 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ofbkge5tm {
  d: path("M2 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.prhskmb-v {
  d: path("M4 16c0 -5 4 -7 8 -7s8 2 8 7");
}

</style>
