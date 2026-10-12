<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="eoqxpyu-f"/><path class="q0m9wlbqy"/><path class="rcetuec_b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:axolotl-sharp" /></template>
<style>
.eoqxpyu-f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12.5c0-2.5 2-4 4.5-4C9 8.5 10 9.5 11 10c4-.25 7-1.5 10 .5c-3.25 2.5-6 3.75-9 3.75L9.9 16H7.25C4.75 16 3 14.5 3 12.5Z");
}

.q0m9wlbqy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 8.5V6.333L8.5 5m.94 4.06l.437-2.187L11.19 5.56M11 10l.786-1.964l1.964-.786m-10 6.25l1.526 1.145l1.974-.395M10 15.4l-.5 2.35m6-3.75l.25 2.25");
}

.rcetuec_b {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 11.25h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
