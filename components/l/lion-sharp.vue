<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="lr1hovb-b"/><path class="ib8p7jb7b"/><path class="af9qykbbr"/><path class="o-ptqvbln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lion-sharp" /></template>
<style>
.af9qykbbr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.25 12.25h.01m3.49 0h.01");
}

.ib8p7jb7b {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.26 10.73a1.5 1.5 0 1 1 1.72-1.72a4.25 4.25 0 0 1 4.04 0a1.5 1.5 0 1 1 1.72 1.72a4.25 4.25 0 1 1-7.48 0Z");
}

.lr1hovb-b {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.39 4.63a2.5 2.5 0 0 1 3.88 2.81A2.5 2.5 0 0 1 19.75 12a2.5 2.5 0 0 1-1.48 4.56a2.5 2.5 0 0 1-3.88 2.81a2.5 2.5 0 0 1-4.78 0a2.5 2.5 0 0 1-3.88-2.81A2.5 2.5 0 0 1 4.25 12a2.5 2.5 0 0 1 1.48-4.56a2.5 2.5 0 0 1 3.88-2.81a2.5 2.5 0 0 1 4.78 0Z");
}

.o-ptqvbln {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 14.25h2l-1 1Zm1 1v1.25h-1.25M12 15.25v1.25h1.25");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
