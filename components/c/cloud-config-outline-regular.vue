<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rbwrj-biq"/><path class="jtt8g10_o"/><path class="d7-beqbwb"/><path class="ikiprn9sq"/><path class="p49_frb7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cloud-config-outline-regular" /></template>
<style>
.d7-beqbwb {
  d: path("M13.5 8v4");
}

.ikiprn9sq {
  d: path("M9 14h6");
}

.jtt8g10_o {
  d: path("M9 10h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p49_frb7e {
  d: path("M10.5 12v4");
}

.rbwrj-biq {
  d: path("M4 18a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 9a5.5 5.5 0 0 1 4.5 9Z");
}

</style>
