<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l1-bc96bi"/><path class="bu8ore6lj"/><path class="hwh3wzbtm"/><path class="f6o19s4sp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ironing-board-duotone-regular" /></template>
<style>
.bu8ore6lj {
  d: path("M3 6h14a3 3 0 0 1 0 6H3Z");
}

.f6o19s4sp {
  d: path("M13 12c1 3 2 6 3 8");
}

.hwh3wzbtm {
  d: path("M7 12c-1 3 -2 6 -3 8");
}

.l1-bc96bi {
  fill: currentColor;
  d: path("M3 6h14a3 3 0 0 1 0 6H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
