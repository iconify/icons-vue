<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="asz-ftbxh"/><path class="zo_l4ub5r"/><path class="iulb4mb6k"/><path class="z35tx4bdc"/><path class="mqnae981n"/><path class="oifr9zbpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:denoise-duotone-regular" /></template>
<style>
.asz-ftbxh {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 6 4 -4 4 4 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iulb4mb6k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mqnae981n {
  d: path("m9 11 3 3 3 -3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.z35tx4bdc {
  d: path("m3 6 4 -4 4 4 4 -4 4 4");
}

.zo_l4ub5r {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 11 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
