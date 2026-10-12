<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="hre0oo70e"/><path class="uosluh_or"/><path class="b4vokcbqq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:horse-sharp" /></template>
<style>
.b4vokcbqq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.5 9.75h.01");
}

.hre0oo70e {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.75 21.25h-7.5c0-2.25.75-4 .75-5.75c-1.25.75-3 1.25-4.75 1.5l-2.5.357v-3.285l.7-.622L10.5 7l1.083-1.083L13.25 5.5l.5-2.5l1.75 2.25c2.75.75 4.75 3.5 4.75 7c0 3.75-2.5 6-2.5 9Z");
}

.uosluh_or {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.25 7.5l2.125 2.125L18 13");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
