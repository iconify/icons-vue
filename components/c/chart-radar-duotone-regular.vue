<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oy5p0_yoh"/><path class="r4un9bb7j"/><path class="kj_xiu02e"/><path class="zwbbmtbru"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-radar-duotone-regular" /></template>
<style>
.kj_xiu02e {
  d: path("m12 4 8 8 -8 8 -8 -8Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oy5p0_yoh {
  fill: currentColor;
  d: path("m12 4 8 8 -8 8 -8 -8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.r4un9bb7j {
  fill: currentColor;
  d: path("m12 8 4 4 -4 4 -4 -4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zwbbmtbru {
  d: path("m12 8 4 4 -4 4 -4 -4Z");
}

</style>
