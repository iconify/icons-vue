<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ygwq4ccpx"/><rect class="oj1gcfcxu"/><path class="akq2cxbrz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dhaba-sign" /></template>
<style>
.akq2cxbrz {
  d: path("M9 11.75h7.5M9 14h4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oj1gcfcxu {
  width: 13px;
  height: 8px;
  x: 6.25px;
  y: 8.75px;
  rx: 1.25px;
}

.ygwq4ccpx {
  d: path("M3.5 2.75v18.5m0-16h15.75m-10.75 0v3.5m8.5-3.5v3.5");
}

</style>
