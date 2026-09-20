<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xz28jbbzy"/><path class="hspl6tj_s"/><path class="pmbwi9b0n"/><path class="o53n0ib2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cost-duotone-regular" /></template>
<style>
.hspl6tj_s {
  d: path("M4 7a8 3 0 0 1 16 0v10a8 3 0 0 1 -16 0Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o53n0ib2h {
  d: path("M4 12a8 3 0 0 0 16 0");
}

.pmbwi9b0n {
  d: path("M4 7a8 3 0 0 0 16 0");
}

.xz28jbbzy {
  fill: currentColor;
  d: path("M4 7a8 3 0 0 1 16 0v10a8 3 0 0 1 -16 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
