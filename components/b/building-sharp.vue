<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="xuwjnbqhw"/><path class="bvqlz6eem"/><path class="im1o2_bki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:building-sharp" /></template>
<style>
.bvqlz6eem {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 6.75h.01m5.99 0h.01M9 10.25h.01m5.99 0h.01M9 13.75h.01m5.99 0h.01");
}

.im1o2_bki {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 21.25V16.5h3.5v4.75");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xuwjnbqhw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 2.75h13.5v18.5H5.25z");
}

</style>
