<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="l5zbv2byh"/><path class="o40hxbbja"/><path class="z144ykbhq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hovercraft-sharp" /></template>
<style>
.l5zbv2byh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 7.5a2.75 2.75 0 0 1 5.5 0m-6.34 6.51l.43-2.52l.16-.99H15.5l.66.75l2.68 3l.66.75h-16z");
}

.o40hxbbja {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.75 12.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.z144ykbhq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 15h18.5v4.25H2.75v-3Z");
}

</style>
