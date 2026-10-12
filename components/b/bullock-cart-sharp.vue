<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="yeqq9bcnz"/><circle class="k02sj3bvq"/><path class="gnfs9sbpb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bullock-cart-sharp" /></template>
<style>
.gnfs9sbpb {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 17.75h.01");
}

.k02sj3bvq {
  cx: 7.75px;
  cy: 17.75px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.yeqq9bcnz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11.5v-7h9.5v7Zm12.75-1.25h4.5v7h-4.5V15Zm0 0l-1.562-1.562L15 6.25m5.25 4l1.563-1.562L21 6.25M12.5 11h3.25");
}

</style>
