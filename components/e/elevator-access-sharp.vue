<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="y_ml4ibwu"/><path class="kq-ipxbat"/><path class="jklof9byt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:elevator-access-sharp" /></template>
<style>
.jklof9byt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.75 15.75V18h2l.5 2m-4.5-2.65a2.1 2.1 0 1 0 2.75 3.15");
}

.kq-ipxbat {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.75 13.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.y_ml4ibwu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h11v18.5h-11zm5.5 0v18.5m9-15.75l2-2.25l2 2.25m-4 3.5l2 2.25l2-2.25");
}

</style>
