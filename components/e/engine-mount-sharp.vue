<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="y5_oc8wua"/><path class="c5omybctg"/><path class="ram43yxyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:engine-mount-sharp" /></template>
<style>
.c5omybctg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 11.25L10.563 13L9.25 14.75m5.5-3.5L13.438 13l1.312 1.75M2.75 17h18.5v4.25H2.75z");
}

.ram43yxyd {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.5 19.1h.01m12.99 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.y5_oc8wua {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75V9m-1-4l2-1m-2 3.25l2-1M7 9h10v8H7z");
}

</style>
