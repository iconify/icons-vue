<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="lejn8kbnn"/><circle class="esuf5po8m"/><path class="n4d9l_7ny"/><path class="by03byron"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:git-tag-sharp" /></template>
<style>
.by03byron {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 12h.01");
}

.esuf5po8m {
  cx: 5.75px;
  cy: 12px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lejn8kbnn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 2.75v7m0 4.5v7");
}

.n4d9l_7ny {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 8.25h6.25l.85.91l1.8 1.93l.85.91l-.85.91l-1.8 1.93l-.85.91h-7.5v-7.5z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
