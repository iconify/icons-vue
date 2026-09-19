<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ny70f4b7n"/><path class="yoimwyq9u"/><path class="lfrwn9hyn"/><path class="ec6otp9um"/><path class="zv1j0mg6o"/><circle class="ir1-og6mv"/><path class="krc9hwk0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bpi-mobile" /></template>
<style>
.ec6otp9um {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.19 14.463c-2.513-1.31-6.498-6.246 1.81-7.35");
}

.ir1-og6mv {
  cx: 24px;
  cy: 5.535px;
  r: 1.035px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.krc9hwk0t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 14.44V6.569m0 10.2V43.5");
}

.lfrwn9hyn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.403 14.44c2.943-.276 4.843-1.563 4.843-3.403s-2.85-2.982-4.843-2.982M24 43.5l-12.188-8.705a2.19 2.19 0 0 1-.884-2.15l2.588-15.079A81 81 0 0 1 24 16.77m0-2.33a46 46 0 0 0-7.572.49");
}

.ny70f4b7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 43.5l12.188-8.705a2.19 2.19 0 0 0 .884-2.15l-2.588-15.079A81 81 0 0 0 24 16.77m0-2.33a46 46 0 0 1 7.572.49");
}

.yoimwyq9u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.81 14.463c2.513-1.31 6.498-6.246-1.81-7.35");
}

.zv1j0mg6o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.597 14.44c-2.943-.276-4.843-1.563-4.843-3.403s2.85-2.982 4.843-2.982");
}

</style>
