<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iuz4k68jh"/><path class="k2duqr8gn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:captions-off" /></template>
<style>
.iuz4k68jh {
  d: path("M8.9 5h12.6v12.6M15.1 19H2.5V6.4");
}

.k2duqr8gn {
  d: path("M7.203 11.191q-.171.387-.171.809q0 .063.004.126t.012.125t.019.125t.028.123t.035.121t.043.118q.023.059.05.116t.057.112t.065.108q.033.053.071.104t.077.1q.04.048.083.094t.09.089t.094.083q.049.04.1.077t.104.07q.054.034.109.064t.112.057t.116.05t.119.042t.121.035t.123.027t.124.019t.126.012t.126.003t.126-.004q.063-.005.125-.013q.063-.008.124-.02q.062-.012.123-.028t.121-.036t.118-.043t.116-.051M16.5 10.25q-.127-.07-.264-.122q-.136-.051-.278-.082t-.287-.041t-.291.001t-.287.043t-.278.084q-.135.052-.262.123t-.242.16M3.5 3.5l17 17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
