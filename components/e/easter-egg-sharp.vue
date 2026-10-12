<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="nw2thcvnl"/><path class="p6rickb5s"/><path class="jwpy7izto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:easter-egg-sharp" /></template>
<style>
.jwpy7izto {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 16.5h.01m2.99.75h.01M15 16.5h.01M12 7.25h.01");
}

.nw2thcvnl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75c3.9 0 7.25 5.75 7.25 11a7.25 7.25 0 0 1-14.5 0c0-5.25 3.35-11 7.25-11Z");
}

.p6rickb5s {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.4 11.25L7.6 13l2.2-1.75L12 13l2.2-1.75L16.4 13l2.2-1.75");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
