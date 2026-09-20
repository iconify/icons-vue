<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f1f6hqh9d"/><circle class="mp-m2ub5s"/><circle class="qn3y7u6ph"/><path class="v_rgm4b0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:crispy-icon-pack" /></template>
<style>
.f1f6hqh9d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.717 2.555a21.5 21.5 0 0 0-13.67 6.242c-8.396 8.396-8.396 22.009 0 30.405s22.01 8.397 30.406.001l-10.619-10.62A6.5 6.5 0 0 1 25.25 30.5a6.5 6.5 0 1 1 4.596-11.096L40.453 8.797a21.5 21.5 0 0 0-16.736-6.242");
}

.mp-m2ub5s {
  cx: 25.25px;
  cy: 24px;
  r: 14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qn3y7u6ph {
  cx: 25.25px;
  cy: 24px;
  r: 3.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v_rgm4b0e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.685 10.565a19 19 0 0 1 0 26.87");
}

</style>
