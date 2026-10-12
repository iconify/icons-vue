<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="d6ht2p1tf"/><path class="urn9fgb8u"/><path class="bbktlbcro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cutting-board-sharp" /></template>
<style>
.bbktlbcro {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 10h7m-7 3h7m-7 3h4.5");
}

.d6ht2p1tf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 6.25h11.5v4h4.5v5.5h-4.5v4h-14V6.25z");
}

.urn9fgb8u {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.75 13h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
