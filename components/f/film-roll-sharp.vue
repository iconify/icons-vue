<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="bv07l1bxs"/><path class="ugjldccos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:film-roll-sharp" /></template>
<style>
.bv07l1bxs {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 3h4v3.25h-4zm-2.5 3.25h9V21h-9zm0 2.5h9m-9 9.75h9m0-9.75h9.5v8h-9.5z");
}

.ugjldccos {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.75 10.75h.01m3.49 0h.01m-3.51 4h.01m3.49 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
