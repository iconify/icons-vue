<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="j7rmb8bxg"/><path class="g2-o--bpj"/><path class="jpkl0fpri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bear-sharp" /></template>
<style>
.g2-o--bpj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 16.25a3.25 2.5 0 1 0 6.5 0a3.25 2.5 0 1 0-6.5 0Z");
}

.j7rmb8bxg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.82 9a2.75 2.75 0 1 1 2.65-2.37a7.5 7.5 0 0 1 7.06 0A2.75 2.75 0 1 1 18.18 9A7.5 7.5 0 1 1 5.82 9Z");
}

.jpkl0fpri {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 15.5h.01M9 11.25h.01m5.99 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
