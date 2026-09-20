<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xzhm7354z"/><path class="o_t5xoern"/><path class="z81xltbwu"/><path class="utcr20lug"/><path class="o9fi6qz7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:budget-alert-duotone-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o_t5xoern {
  fill: currentColor;
  d: path("M11 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.o9fi6qz7l {
  d: path("M11 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.utcr20lug {
  d: path("M12 13v5");
}

.xzhm7354z {
  fill: currentColor;
  d: path("M2 7a3 3 0 0 1 3 -3h14a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.z81xltbwu {
  d: path("M2 7a3 3 0 0 1 3 -3h14a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3");
}

</style>
