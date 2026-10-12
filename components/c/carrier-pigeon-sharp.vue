<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="fknk_hbuq"/><path class="pqr6mcxke"/><path class="se971gh0e"/><path class="dtgpiabpt"/><path class="k-1qlkbpp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:carrier-pigeon-sharp" /></template>
<style>
.dtgpiabpt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.75 16.25V19h1m1.5-1.25h6v3.5h-6z");
}

.fknk_hbuq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8c.75-2.5 2.25-3.5 4-3.5c2 0 3.25 1.25 3.5 3l11 2l-3.5 3.25c-1.75 3-5 4.25-8 3.5C6.5 15.5 5 12.5 5.5 9.5Z");
}

.k-1qlkbpp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.75 19.25l1.1.8l.4.32l.4-.32l1.1-.8");
}

.pqr6mcxke {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 7.5c1 3 3.75 4.5 6.75 4");
}

.se971gh0e {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 7h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
