<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ov_5e1bbh"/><rect class="pl58nzbde"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cannula" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ov_5e1bbh {
  d: path("M2.75 12h5m1-2zq1 0 1.15-.99l.45-3.02Q10.5 5 11.5 5h.25q1 0 1.15.99l.45 3.02q.15.99 1.15.99t1 1v2q0 1-1 1t-1.15.99l-.45 3.02q-.15.99-1.15.99h-.25q-1 0-1.15-.99l-.45-3.02Q9.75 14 8.75 14t-1-1v-2q0-1 1-1");
}

.pl58nzbde {
  width: 3.25px;
  height: 3px;
  x: 18px;
  y: 10.5px;
  rx: 1.25px;
}

</style>
