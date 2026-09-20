<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="m_jiv1ilq"/><circle class="nc7-apm1q"/><path class="qkhhcmu2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:inter" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.m_jiv1ilq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.62 24.332a2.88 2.88 0 0 1 2.88-2.88m-2.881 0v7.633");
}

.nc7-apm1q {
  cx: 11.373px;
  cy: 18.923px;
  r: 0.75px;
  fill: currentColor;
}

.qkhhcmu2m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.696 19.075v8.57c0 .796.645 1.44 1.44 1.44h.433m-1.873-7.633h1.873m-15.069 0h1.873v7.633m8.561.001v-4.754a2.88 2.88 0 1 0-5.761 0v4.753m-.001-4.753v-2.88m18.297 6.18a2.88 2.88 0 0 1-5.384-1.427v-1.873a2.88 2.88 0 1 1 5.761 0v.936h-5.761");
}

</style>
