<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="na_sj_b_j"/><path class="cktduhxcf"/><path class="f018rabbl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:git-commit-vertical-outline-regular" /></template>
<style>
.cktduhxcf {
  d: path("M8.5 12a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

.f018rabbl {
  d: path("M12 15.5V21");
}

.na_sj_b_j {
  d: path("M12 3v5.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
