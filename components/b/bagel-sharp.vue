<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="kirs8hmsl"/><path class="u8k2u_big"/><path class="q-5f3ccza"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bagel-sharp" /></template>
<style>
.kirs8hmsl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4.75h18v5H3z");
}

.q-5f3ccza {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 13.5c1.4 0 1.4-1 2.75-1s1.4 1 2.75 1s1.4-1 2.75-1s1.4 1 2.75 1s1.4-1 2.75-1s1.4 1 2.75 1M3 16.25h18v5H3z");
}

.u8k2u_big {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 7.25h.01m4.49 0h.01m4.49 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
