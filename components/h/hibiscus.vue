<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="whqn7xzzh"/><path class="fhhou0bqf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hibiscus" /></template>
<style>
.fhhou0bqf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.895 10.01h.01");
}

.whqn7xzzh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.65 9.01a3.36 3.36 0 1 1 4.7 0a3.36 3.36 0 1 1 1.45 4.48a3.36 3.36 0 1 1-3.8 2.76a3.36 3.36 0 1 1-3.8-2.76a3.36 3.36 0 1 1 1.45-4.48M12 12.25l5.47-1.78");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
