<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse transform="rotate(-15.69 24.017 24.017)" class="h_mv6dbdj"/><path class="w8ay0u02w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:francomanca" /></template>
<style>
.h_mv6dbdj {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 20.04px;
  ry: 10.47px;
}

.w8ay0u02w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.18 20.13c-8.87-.92-21.08 2.56-19.47 7.52s10.6 4.61 18.9 1s10.25-9 7.26-11.35s-11.3-1.21-14.18-.52");
}

</style>
