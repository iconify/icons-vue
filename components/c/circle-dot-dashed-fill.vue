<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ipak1qbro"/><path clip-rule="evenodd" class="qes2l5bqq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-dot-dashed-fill" /></template>
<style>
.ipak1qbro {
  d: path("M21.877 10.436C22.041 11.472 22.041 12.528 21.877 13.564M20.09 17.878C19.473 18.727 18.727 19.473 17.878 20.09M13.564 21.877C12.528 22.041 11.472 22.041 10.436 21.877M6.122 20.09C5.273 19.473 4.527 18.727 3.91 17.878M2.123 13.564C1.959 12.528 1.959 11.472 2.123 10.436M3.91 6.122C4.527 5.273 5.273 4.527 6.122 3.91M10.436 2.123C11.472 1.959 12.528 1.959 13.564 2.123M17.878 3.91C18.727 4.527 19.473 5.273 20.09 6.122");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qes2l5bqq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 12C14 13.105 13.105 14 12 14C10.895 14 10 13.105 10 12C10 10.895 10.895 10 12 10C13.105 10 14 10.895 14 12Z");
  stroke: none;
}

</style>
