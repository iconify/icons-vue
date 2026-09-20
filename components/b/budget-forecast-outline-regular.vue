<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="x9ne0caxf"/><path class="ks612kq_w"/><path class="boj5jfb_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:budget-forecast-outline-regular" /></template>
<style>
.boj5jfb_k {
  d: path("M13.5 9.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ks612kq_w {
  d: path("m7 17 5 -5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.x9ne0caxf {
  d: path("M7 8h12");
}

</style>
