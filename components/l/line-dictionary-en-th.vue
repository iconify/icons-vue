<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lel256k6n"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:line-dictionary-en-th" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.lel256k6n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.442 21.833v-8.015l6.062 8.015v-8.015m2.246 4.008h2.015m2.005 4.007h-4.02v-8.015h4.02m-16.497 0v8.015m-2.005-8.015h4.019m-4.019 8.015h4.019m-10.028-8.015v8.015h4.02m-.77 11.368a1.947 1.947 0 0 1-3.64-.964v-1.265a1.947 1.947 0 0 1 3.895 0v.633h-3.895m21.396-.635a1.947 1.947 0 0 1 3.895 0v3.214m-3.895-7.79v7.79m-4.387-5.033h2.044M31.9 27.418v5.793c0 .538.436.974.974.974h.292m-13.303-.001v-5.161m3.895 5.161V30.97a1.947 1.947 0 0 0-3.895 0m8.916-4.308l-2.921 9.883M10.5 42.5v-37");
}

</style>
