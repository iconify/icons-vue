<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ds-ud47kp"/><rect class="y5k2n1-gv"/><rect class="cjdr0xbiz"/><rect class="ib3t7mb0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:grid-dots" /></template>
<style>
.cjdr0xbiz {
  width: 6.5px;
  height: 6.5px;
  x: 3.75px;
  y: 13.75px;
  rx: 1.75px;
}

.ds-ud47kp {
  width: 6.5px;
  height: 6.5px;
  x: 3.75px;
  y: 3.75px;
  rx: 1.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ib3t7mb0k {
  width: 6.5px;
  height: 6.5px;
  x: 13.75px;
  y: 13.75px;
  rx: 1.75px;
}

.y5k2n1-gv {
  width: 6.5px;
  height: 6.5px;
  x: 13.75px;
  y: 3.75px;
  rx: 1.75px;
}

</style>
