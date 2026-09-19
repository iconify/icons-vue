<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y-z54wbbl"/><circle class="mdf6ehbyd"/><circle class="c7tszjbsg"/><path class="yhg968bwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cnn-turk" /></template>
<style>
.c7tszjbsg {
  cx: 17.266px;
  cy: 29.025px;
  r: 0.8px;
  fill: currentColor;
}

.mdf6ehbyd {
  cx: 20.066px;
  cy: 29.025px;
  r: 0.8px;
  fill: currentColor;
}

.y-z54wbbl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 8.395v16.13L30.94 8.395v16.13L18.38 8.395v16.13h-5.816a8.065 8.065 0 0 1 0-16.13h2.829m12.237 31.21v-8h2.6c1.5 0 2.7 1.2 2.7 2.7s-1.2 2.7-2.7 2.7h-2.6m2.698-.003l2.502 2.503m-28.33-7.9h5.2m-2.6 8v-8m8.966 0v5.3c0 1.5 1.2 2.7 2.6 2.7s2.6-1.2 2.6-2.7v-5.3");
}

.yhg968bwk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.3 31.605v8m0-2.8l4.2-5.2m0 8l-3.2-4");
}

</style>
