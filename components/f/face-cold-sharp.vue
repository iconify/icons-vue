<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="d3yum4nir"/><path class="pkxclebiu"/><path class="txc_unbkh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-cold-sharp" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.d3yum4nir {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.15 6.5h1.1l-.11.39l-.53 1.97l-.11.39l-.11-.39l-.53-1.97l-.11-.39zm3.5-.5h1.1l-.1.39l-.55 2.22L12 9l-.1-.39l-.55-2.22l-.1-.39zm3.5.5h1.1l-.11.39l-.53 1.97l-.11.39l-.11-.39l-.53-1.97l-.11-.39z");
}

.pkxclebiu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 11.5h.01m5.99 0h.01");
}

.txc_unbkh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8 16.75l1.33-1l1.33 1l1.33-1l1.33 1l1.33-1l1.33 1");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
