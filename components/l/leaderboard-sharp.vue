<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="tfmmtps3w"/><path class="gxj0gh4aj"/><path class="np6v2ksmb"/><path class="y0ccz-u_r"/><path class="b7b96hqda"/><path class="ufcahkbfz"/><path class="izktscztu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:leaderboard-sharp" /></template>
<style>
.b7b96hqda {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 12H14M2.75 16.75h11.5v4.5H2.75z");
}

.gxj0gh4aj {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.5 5h.01");
}

.izktscztu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 19h3");
}

.np6v2ksmb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 5h7M2.75 9.75h15v4.5h-15z");
}

.tfmmtps3w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v4.5H2.75z");
}

.ufcahkbfz {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.5 19h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.y0ccz-u_r {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.5 12h.01");
}

</style>
