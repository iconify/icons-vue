<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="lk6ns0b7f"/><path class="csx_8sbvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:game-console-sharp" /></template>
<style>
.csx_8sbvm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 12h.01M18 12h.01");
}

.lk6ns0b7f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.75h18.5v6.5H2.75zM6 12h2.5m-1.25-1.25v2.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
