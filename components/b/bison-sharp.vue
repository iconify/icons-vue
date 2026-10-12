<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="d8yrm_bvz"/><path class="l1_qt8bow"/><path class="klgrndbjw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bison-sharp" /></template>
<style>
.d8yrm_bvz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 6.5C11 4.25 13 3.25 15 3.25c2.5 0 4 1.5 4.5 3.5l.75 3c.3 1.25.5 2.5.5 3.75v6.75H18.5v-3.5h-5.75v3.5H10V16.5H9l-1.75 2l-1.75-1.75L3.25 16v-2l.25-3.5l.386-3.091L6.75 7Z");
}

.klgrndbjw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 10.25h.01");
}

.l1_qt8bow {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 7.25L4.173 6.067L5 4");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
