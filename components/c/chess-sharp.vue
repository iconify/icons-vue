<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="gspo7vi8k"/><path class="hot5z2l8m"/><path class="j6mep3xum"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chess-sharp" /></template>
<style>
.gspo7vi8k {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 15.75c0-2.75 1.5-4.5 2.5-6c-1.5.25-3.25.75-4.5 2L4.5 9.5C6 6.75 8.25 4.25 12.25 3.75l.75-1L14.25 4c2.5 1.25 4.25 4 4.25 7.5v4.25Z");
}

.hot5z2l8m {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.75 7h.01");
}

.j6mep3xum {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 18.25h14v3H5z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
