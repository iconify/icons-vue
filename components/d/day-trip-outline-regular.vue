<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="isuawcbcl"/><path class="zkgvk4bog"/><path class="eqwjlk9zl"/><path class="gd-e99l8k"/><path class="bod4n0b3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:day-trip-outline-regular" /></template>
<style>
.bod4n0b3z {
  d: path("M2 18h20");
}

.eqwjlk9zl {
  d: path("m4 5 3 3");
}

.gd-e99l8k {
  d: path("m20 5 -3 3");
}

.isuawcbcl {
  d: path("M7.5 11a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zkgvk4bog {
  d: path("M12 2v3");
}

</style>
