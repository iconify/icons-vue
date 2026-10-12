<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="nqt-e0_0q"/><path class="qlv5wkfuj"/><path class="g82as4s4v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:infusion-pump-sharp" /></template>
<style>
.g82as4s4v {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 15.5h.01m3.24 0h.01m3.24 0h.01");
}

.nqt-e0_0q {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 2.75v2m0 15.5v1M4.75 4.75h14.5v15.5H4.75z");
}

.qlv5wkfuj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 7.5h9V12h-9z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
