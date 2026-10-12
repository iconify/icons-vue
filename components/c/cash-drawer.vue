<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="i1_2xsftx"/><path class="bywa281xq"/><rect class="dn4p92b7r"/><path class="zev7nzb0i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cash-drawer" /></template>
<style>
.bywa281xq {
  d: path("M9.5 6.63h5");
}

.dn4p92b7r {
  width: 15.5px;
  height: 8.75px;
  x: 4.25px;
  y: 12.5px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i1_2xsftx {
  width: 18.5px;
  height: 6.75px;
  x: 2.75px;
  y: 3.25px;
  rx: 2px;
}

.zev7nzb0i {
  d: path("M8.13 12.5v8.75M12 12.5v8.75m3.88-8.75v8.75");
}

</style>
