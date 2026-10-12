<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ycxpx3b3c"/><path class="v4ewq5b7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dispatch-sharp" /></template>
<style>
.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.v4ewq5b7w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.5 6.5h.01");
}

.ycxpx3b3c {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 14.75h6.5v6.5h-6.5zM9.25 18h7.25v-4.75m0-10.5a3.75 3.75 0 0 1 3.75 3.75c0 3.58-3.75 6.5-3.75 6.5s-3.75-2.93-3.75-6.5a3.75 3.75 0 0 1 3.75-3.75Z");
}

</style>
