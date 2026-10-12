<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="z73fyv35v"/><path class="qmypepvbg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:buildings-sharp" /></template>
<style>
.qmypepvbg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.25 7h.01m2.99 0h.01m-3.01 4h.01m2.99 0h.01m-3.01 4h.01m2.99 0h.01m8.49-2.25h.01m-.01 3.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.z73fyv35v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 2.75h9v18.5h-9zm11.5 6h6v12.5h-6z");
}

</style>
