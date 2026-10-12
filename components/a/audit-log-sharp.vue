<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="uwe7-3bdh"/><path class="h3csp_bzj"/><path class="k28pglbkd"/><circle class="q9g99y-wz"/><path class="um3neob_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:audit-log-sharp" /></template>
<style>
.h3csp_bzj {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 7h.01M6 11h.01M6 15h.01");
}

.k28pglbkd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 7h4.75m-4.75 4h4.75m-4.75 4h2");
}

.q9g99y-wz {
  cx: 17px;
  cy: 16.25px;
  r: 4px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.um3neob_o {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 14.25v2l1.25 1.25");
}

.uwe7-3bdh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h14v17.5h-14z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
