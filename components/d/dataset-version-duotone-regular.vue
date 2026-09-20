<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qu3m42btf"/><path class="u4nee_bsy"/><path class="g3f86pbne"/><path class="ojk--hbsz"/><path class="qlmv4fbzq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dataset-version-duotone-regular" /></template>
<style>
.g3f86pbne {
  d: path("M6 4.25A1.75 1.75 0 0 1 7.75 2.5h11.5A1.75 1.75 0 0 1 21 4.25 1.75 1.75 0 0 1 19.25 6H7.75A1.75 1.75 0 0 1 6 4.25");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ojk--hbsz {
  d: path("M3 11a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.qlmv4fbzq {
  d: path("M6 14.5h12");
}

.qu3m42btf {
  fill: currentColor;
  d: path("M6 4.25A1.75 1.75 0 0 1 7.75 2.5h11.5A1.75 1.75 0 0 1 21 4.25 1.75 1.75 0 0 1 19.25 6H7.75A1.75 1.75 0 0 1 6 4.25");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.u4nee_bsy {
  fill: currentColor;
  d: path("M3 11a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
