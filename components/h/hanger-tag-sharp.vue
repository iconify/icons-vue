<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="d_j7oxdeq"/><path class="u36aqldlt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hanger-tag-sharp" /></template>
<style>
.d_j7oxdeq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 4.5A1.75 1.75 0 1 1 12 6.25V7m0 0l7.9 5l3.129 1.937l-3.679-.087H4.65l-3.679.087L4.1 12Zm2.05 10.75l1.65-1.5l.55-.5l.55.5l1.65 1.5l.55.5v3h-5.5v-3z");
}

.u36aqldlt {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.25 18.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
