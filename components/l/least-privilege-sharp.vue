<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="tfmmtps3w"/><path class="y3h33n1gr"/><path class="pez39ybee"/><circle class="x5hbu-ore"/><path class="lafksnb1n"/><path class="kqwa8bcgg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:least-privilege-sharp" /></template>
<style>
.kqwa8bcgg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.25 19h.01");
}

.lafksnb1n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 16.75h18.5v4.5H2.75z");
}

.pez39ybee {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9.75h18.5v4.5H2.75z");
}

.tfmmtps3w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v4.5H2.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.x5hbu-ore {
  cx: 19px;
  cy: 12px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y3h33n1gr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.25 5h.01");
}

</style>
