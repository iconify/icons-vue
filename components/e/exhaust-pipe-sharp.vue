<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ma4-zsbwr"/><path class="xj24ni17m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:exhaust-pipe-sharp" /></template>
<style>
.ma4-zsbwr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12h11.25l.58-.48l.34-.29l.58-.48v7.5l-.58-.48l-.34-.29l-.58-.48h-12v-5zm3 5v3");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xj24ni17m {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.5 14.5h.01m-.51-5h.01M16 5.5h.01");
}

</style>
