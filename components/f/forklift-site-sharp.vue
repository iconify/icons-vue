<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="chh9hbb_j"/><circle class="sf02ieb1s"/><circle class="r-x-f1bxv"/><path class="mncn-x6_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:forklift-site-sharp" /></template>
<style>
.chh9hbb_j {
  d: path("M3.75 12.5H6V5h5.85l.21.72l2.19 6.78v4H2.75v-4zm0 4h9.5");
}

.mncn-x6_n {
  d: path("M17.5 3.5v14h3.75");
}

.r-x-f1bxv {
  cx: 11.75px;
  cy: 18.75px;
  r: 2.25px;
}

.sf02ieb1s {
  cx: 5.75px;
  cy: 18.75px;
  r: 2.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
