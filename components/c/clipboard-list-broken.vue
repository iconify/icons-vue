<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="h3lwipb0h"/><path class="ce3b4y7bf"/><path class="pi6wd7bqh"/><path class="e5q6nznvv"/><path class="x2je1dw0q"/><path class="zxxxt7bqz"/><path class="my5268blj"/><path class="ndq0ugbyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clipboard-list-broken" /></template>
<style>
.ce3b4y7bf {
  d: path("M7 14H7.5");
}

.e5q6nznvv {
  d: path("M7 17.5H7.5");
}

.h3lwipb0h {
  d: path("M10.5 14L17 14");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.my5268blj {
  d: path("M9.5 6H14.5C15.3284 6 16 5.32843 16 4.5V3.5C16 2.67157 15.3284 2 14.5 2H9.5C8.67157 2 8 2.67157 8 3.5V4.5C8 5.32843 8.67157 6 9.5 6Z");
}

.ndq0ugbyy {
  d: path("M21 16.0002C21 18.8286 21 20.2429 20.1213 21.1215C19.2426 22.0002 17.8284 22.0002 15 22.0002H9C6.17157 22.0002 4.75736 22.0002 3.87868 21.1215C3 20.2429 3 18.8286 3 16.0002V13.0002M16 4.00195C18.175 4.01406 19.3529 4.11051 20.1213 4.87889C21 5.75757 21 7.17179 21 10.0002V12.0002M8 4.00195C5.82497 4.01406 4.64706 4.11051 3.87868 4.87889C3.11032 5.64725 3.01385 6.82511 3.00174 9");
}

.pi6wd7bqh {
  d: path("M7 10.5H7.5");
}

.x2je1dw0q {
  d: path("M10.5 10.5H17");
}

.zxxxt7bqz {
  d: path("M10.5 17.5H17");
}

</style>
