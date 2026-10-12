<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wjoswmr2r"/><rect class="nbxybzw_j"/><path class="z0zo5-trn"/><rect class="suoavkz9r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dock-door" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nbxybzw_j {
  width: 12.5px;
  height: 7.5px;
  x: 5.75px;
  y: 5.75px;
  rx: 0.75px;
}

.suoavkz9r {
  width: 5.5px;
  height: 4.5px;
  x: 9.25px;
  y: 16.75px;
  rx: 0.75px;
}

.wjoswmr2r {
  d: path("M2.75 21.25V4.75a2 2 0 0 1 2-2h14.5a2 2 0 0 1 2 2v16.5");
}

.z0zo5-trn {
  d: path("M5.75 8.25h12.5m-12.5 2.5h12.5");
}

</style>
