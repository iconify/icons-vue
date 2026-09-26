<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cj7-b7bdm"/><path class="j7ophtquh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:home-plus-duotone" /></template>
<style>
.cj7-b7bdm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 12L21 20C20.9999 21.6568 19.6568 23 18 23L4 23C2.34318 23 1.00011 21.6568 1 20L1 11.9268C1.00002 11.0452 1.38775 10.20775 2.06055 9.63773L9.0605 3.70707C10.0406 2.8767 11.4213 2.7737 12.5008 3.398C12.8099 3.5767 13 3.907 13 4.264L13 8C13 9.6569 14.3431 11 16 11L20 11C20.5523 11 21 11.4477 21 12Z");
  stroke: none;
}

.j7ophtquh {
  d: path("M8 22L8 15L14 15L14 22M19 2V8M16 5H22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
