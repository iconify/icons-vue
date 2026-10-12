<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qr_tqn_nr"/><rect class="d2o9d2bhb"/><path class="ufxi_ob1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hotel-check-out" /></template>
<style>
.d2o9d2bhb {
  width: 11px;
  height: 12.5px;
  x: 2.75px;
  y: 8.25px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qr_tqn_nr {
  d: path("M6 8.25v-2a1 1 0 0 1 1-1h2.5a1 1 0 0 1 1 1v2");
}

.ufxi_ob1b {
  d: path("M6.25 11.75v5.5m4-5.5v5.5M16 14.5h5.25m-3-3l3 3l-3 3");
}

</style>
