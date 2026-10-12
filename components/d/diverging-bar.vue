<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g2p_ol6bq"/><rect class="deam3_whz"/><rect class="cup79wbtk"/><rect class="t1o9rac8i"/><rect class="kkmc5kbrr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:diverging-bar" /></template>
<style>
.cup79wbtk {
  width: 5px;
  height: 3.5px;
  x: 4.75px;
  y: 10.25px;
  rx: 1px;
}

.deam3_whz {
  width: 7px;
  height: 3.5px;
  x: 14.25px;
  y: 3.75px;
  rx: 1px;
}

.g2p_ol6bq {
  d: path("M12 2.75v18.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kkmc5kbrr {
  width: 4px;
  height: 3.5px;
  x: 14.25px;
  y: 16.75px;
  rx: 1px;
}

.t1o9rac8i {
  width: 7px;
  height: 3.5px;
  x: 2.75px;
  y: 16.75px;
  rx: 1px;
}

</style>
