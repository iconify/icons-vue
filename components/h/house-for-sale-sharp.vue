<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="peoliacxi"/><path class="zy152hq3r"/><path class="g1kxs5bwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:house-for-sale-sharp" /></template>
<style>
.g1kxs5bwq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.25 16.25h.01");
}

.peoliacxi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 18.75V8.55l.78-.62l5.69-4.55l.78-.63l.78.63l5.69 4.55l.78.62v1.7a7 7 0 0 0-7 7v2.5h-7.5z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zy152hq3r {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.9 14h2.85l.64.64l2.22 2.22l.64.64l-.64.64l-2.47 2.47l-.64.64l-.64-.64l-2.22-2.22l-.64-.64V14z");
}

</style>
