<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g9s9057mj"/><path class="btch367cg"/><path class="pdx7buv0t"/><path class="oordrjbbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:anxiety-duotone-regular" /></template>
<style>
.btch367cg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7 6 3 3 -3 3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g9s9057mj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 21v-4c-2 -2 -3 -5 -3 -8a7 7 0 0 1 14 -1c0 2 2 3 2 4s-1 1 -2 1v3a2 2 0 0 1 -2 2h-3v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oordrjbbh {
  d: path("m7 6 3 3 -3 3 3 3");
}

.pdx7buv0t {
  d: path("M6 21v-4c-2 -2 -3 -5 -3 -8a7 7 0 0 1 14 -1c0 2 2 3 2 4s-1 1 -2 1v3a2 2 0 0 1 -2 2h-3v3");
}

</style>
