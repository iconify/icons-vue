<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="akmah8e_a"/><rect class="q0_gb6qzx"/><path class="ph_pysbzh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arrival" /></template>
<style>
.akmah8e_a {
  d: path("M7.5 5.25v-2.5m9 2.5v-2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ph_pysbzh {
  d: path("M6 9.5h5.5m-5.5 5h5.5m6.75-3.5l-3.5 3.5m0-3.25v3.25H18");
}

.q0_gb6qzx {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 5.25px;
  rx: 2px;
}

</style>
