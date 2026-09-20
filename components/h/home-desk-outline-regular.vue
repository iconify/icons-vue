<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kamdbib6v"/><path class="v-q4myyjv"/><path class="n2ya_p02p"/><path class="h5yksf4iw"/><path class="e3fkgnlsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:home-desk-outline-regular" /></template>
<style>
.e3fkgnlsf {
  d: path("M13 16h7");
}

.h5yksf4iw {
  d: path("M13 12h7");
}

.kamdbib6v {
  d: path("M2 7h20");
}

.n2ya_p02p {
  d: path("M13 7v13h7V7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v-q4myyjv {
  d: path("M4 7v13");
}

</style>
