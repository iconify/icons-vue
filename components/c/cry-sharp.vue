<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="eazee3bcp"/><path class="goa6xmsjx"/><path class="vh3vtabuk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cry-sharp" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.eazee3bcp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.25 7.75l2.5-1m7 1l-2.5-1");
}

.goa6xmsjx {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 10.25h.01m5.99 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vh3vtabuk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.75 17l1.029-1.25h2.442L14.25 17M7 12.75l1 1.462v.688a1 1 0 0 1-2 0v-.688z");
}

</style>
