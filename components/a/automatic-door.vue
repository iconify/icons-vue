<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wjoswmr2r"/><rect class="yqgfjhb7f"/><rect class="nge3bghnh"/><path class="vb_gdqb7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:automatic-door" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nge3bghnh {
  width: 3.5px;
  height: 14.5px;
  x: 15.25px;
  y: 6.75px;
  rx: 1px;
}

.vb_gdqb7j {
  d: path("M10.75 11.75L9.5 13.5l1.25 1.75m2.5-3.5l1.25 1.75l-1.25 1.75m-2.75-10h3");
}

.wjoswmr2r {
  d: path("M2.75 21.25V4.75a2 2 0 0 1 2-2h14.5a2 2 0 0 1 2 2v16.5");
}

.yqgfjhb7f {
  width: 3.5px;
  height: 14.5px;
  x: 5.25px;
  y: 6.75px;
  rx: 1px;
}

</style>
