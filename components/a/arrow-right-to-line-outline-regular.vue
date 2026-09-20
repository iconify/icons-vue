<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mhila7bcl"/><path class="jka0cfj-k"/><path class="egsaq3b2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-right-to-line-outline-regular" /></template>
<style>
.egsaq3b2f {
  d: path("m12 8 4 4 -4 4");
}

.jka0cfj-k {
  d: path("M4 12h12");
}

.mhila7bcl {
  d: path("M20 7v10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
