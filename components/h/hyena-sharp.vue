<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="rkpvbzx8h"/><path class="wa8u43bsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hyena-sharp" /></template>
<style>
.rkpvbzx8h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10.25V9.167l1.25-.417L7 7.5l.25-2.25l.246-1.474l.954 1.074L10 6.75c3 0 6.5 2 9.25 5.5l1.5 1.917V20h-2.5v-3.5h-5.5l-1 3.5h-2.5l.5-5L8 13l-2.5-1.25H3z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wa8u43bsb {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.25 10.25h.01m3.24 3h.01m-3.76.5h.01M7.5 9.25h.01");
}

</style>
