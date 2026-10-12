<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="fwph8mbzq"/><path class="y_9og4gqt"/><path class="vtgepkbql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-cowboy-sharp" /></template>
<style>
.fwph8mbzq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 12.75a7.75 7.75 0 0 0 15.5 0Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vtgepkbql {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 17.25L12 18.536l2.25-1.286M2.75 8c2.5 1.5 6 2.1 9.25 2.1s6.75-.6 9.25-2.1M7.75 9.6l.75-5.35l.308-1.745L10.3 3.4L12 4.5l1.7-1.1l1.492-.895l.308 1.745l.75 5.35");
}

.y_9og4gqt {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 14.75h.01m5.49 0h.01");
}

</style>
