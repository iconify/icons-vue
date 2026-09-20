<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kamdbib6v"/><path class="pqojzri_o"/><path class="sno-u_b6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:laundry-day-outline-regular" /></template>
<style>
.kamdbib6v {
  d: path("M2 7h20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pqojzri_o {
  d: path("M6 7v7h4V7");
}

.sno-u_b6h {
  d: path("M14 7v10h4V7");
}

</style>
