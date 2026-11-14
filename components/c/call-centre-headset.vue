<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w9elh_16j"/><path class="fqgbt_byl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:call-centre-headset" /></template>
<style>
.fqgbt_byl {
  d: path("M5 12za1.75 1.75 0 0 1 1.75 1.75v2.5A1.75 1.75 0 0 1 5 18a1.75 1.75 0 0 1-1.75-1.75v-2.5A1.75 1.75 0 0 1 5 12m14 0za1.75 1.75 0 0 1 1.75 1.75v2.5A1.75 1.75 0 0 1 19 18a1.75 1.75 0 0 1-1.75-1.75v-2.5A1.75 1.75 0 0 1 19 12M5 18q0 3.5 4.5 3.5H12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w9elh_16j {
  d: path("M5 13v-2a7 7 0 0 1 14 0v2");
}

</style>
