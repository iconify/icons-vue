<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="yx0qaibdx"/><circle class="fdj2t-bow"/><circle class="ejxhftm9h"/><path class="wr2docblg"/><path class="qykcu7_xm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bouquet-flowers-sharp" /></template>
<style>
.ejxhftm9h {
  cx: 12px;
  cy: 5px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.fdj2t-bow {
  cx: 18px;
  cy: 7.5px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qykcu7_xm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 9.5L9 11.75m7.75-2.25L15 11.75M12 8v3.75m-5.6 0h12.1l-.4.8l-3.95 7.9l-.4.8h-3.5l-.4-.8l-3.95-7.9l-.4-.8zm2.1 3.5h7");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wr2docblg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 7.5h.01M18 7.5h.01M12 5h.01");
}

.yx0qaibdx {
  cx: 6px;
  cy: 7.5px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
