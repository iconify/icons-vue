<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="usr8x8mtt"/><path class="tykcjtbvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-big-down-duotone-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tykcjtbvl {
  d: path("m12 21 -9 -9h5V3h8v9h5Z");
}

.usr8x8mtt {
  fill: currentColor;
  d: path("m12 21 -9 -9h5V3h8v9h5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
