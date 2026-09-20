<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hthehj4ml"/><path class="u4sowhi7h"/><path class="a0lcnrc-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:calorie-outline-regular" /></template>
<style>
.a0lcnrc-j {
  d: path("M18 16a6 6 0 0 1 -12 0");
}

.hthehj4ml {
  d: path("M12 3c1.5 3 4 4 4 7a4 4 0 1 1 -8 0c0 -2.5 2 -3 2 -4.5 0.5 1 2 1 2 -2.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u4sowhi7h {
  d: path("M4 16h16");
}

</style>
