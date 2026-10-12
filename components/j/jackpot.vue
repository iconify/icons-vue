<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="eunlwnqhv"/><rect class="gyr5s2cuc"/><rect class="cs_wshbfr"/><path class="tidcfn3kn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jackpot" /></template>
<style>
.cs_wshbfr {
  width: 6px;
  height: 7.25px;
  x: 15.25px;
  y: 14px;
  rx: 1.5px;
}

.eunlwnqhv {
  width: 6px;
  height: 7.25px;
  x: 2.75px;
  y: 14px;
  rx: 1.5px;
}

.gyr5s2cuc {
  width: 6.5px;
  height: 10.75px;
  x: 8.75px;
  y: 10.5px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tidcfn3kn {
  d: path("M2.75 17.5h6m6.5 0h6M8.75 14h6.5m-6.5 3.5h6.5M12 2.75q.27 1.98 2.25 2.25q-1.98.27-2.25 2.25Q11.73 5.27 9.75 5q1.98-.27 2.25-2.25");
}

</style>
