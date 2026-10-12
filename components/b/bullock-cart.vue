<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="v27msndbx"/><circle class="k02sj3bvq"/><path class="gnfs9sbpb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bullock-cart" /></template>
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

.v27msndbx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11.5V9a4.5 4.5 0 0 1 4.5-4.5H8A4.5 4.5 0 0 1 12.5 9v2.5Zm12.75-1.25h4.5V15A2.25 2.25 0 0 1 18 17.25A2.25 2.25 0 0 1 15.75 15Zm0 0c-1-1-1.25-2.5-.75-4m5.25 4c1-1 1.25-2.5.75-4M12.5 11h3.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
