<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bm1a0ccnq"/><path class="i7kaf-qlz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:health-check-duotone-regular" /></template>
<style>
.bm1a0ccnq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h5V6h4v12h4v-6h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i7kaf-qlz {
  d: path("M3 12h5V6h4v12h4v-6h5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
