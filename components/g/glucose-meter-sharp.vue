<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="hlqao5bdx"/><path class="l5m6etbzo"/><path class="ouz6u8bkn"/><path class="sf13iz7zl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:glucose-meter-sharp" /></template>
<style>
.hlqao5bdx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 3.5h2.5v4.75h-2.5zm-6 4.75h13v13h-13z");
}

.l5m6etbzo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 11.25h7v3.5h-7Z");
}

.ouz6u8bkn {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.25 18h.01");
}

.sf13iz7zl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19 2.75c1 1.3 2 2.3 2 3.4a2 2 0 0 1-4 0c0-1.1 1-2.1 2-3.4Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
