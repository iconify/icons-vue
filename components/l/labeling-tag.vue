<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n_tq67bxo"/><path class="uc29vybnn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:labeling-tag" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n_tq67bxo {
  d: path("M4.25 2.75h4.5q1.5 0 2.56 1.06l4.88 4.88q1.06 1.06 0 2.12l-5.38 5.38q-1.06 1.06-2.12 0l-4.88-4.88q-1.06-1.06-1.06-2.56v-4.5q0-1.5 1.5-1.5");
}

.uc29vybnn {
  d: path("M6.75 5.5a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 1 1 0-2.5m7 12.75L16 20.5l5-5");
}

</style>
