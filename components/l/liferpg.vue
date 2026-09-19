<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="x8aggebjb"/><circle class="p08ljnbog"/><circle class="m0gl09bbt"/><circle class="gtimi7blm"/><path class="ujjpp5h6w"/><circle class="jzqv_yb3c"/><path class="cvuivhecm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:liferpg" /></template>
<style>
.cvuivhecm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.632 22.995v-1.563m-3.049-1.484h1.564m1.485-3.046v1.563m3.048 1.483h-1.564");
}

.gtimi7blm {
  cx: 33.545px;
  cy: 22.855px;
  r: 1.165px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jzqv_yb3c {
  cx: 24px;
  cy: 16.858px;
  r: 1.703px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m0gl09bbt {
  cx: 30.731px;
  cy: 20.044px;
  r: 1.165px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.p08ljnbog {
  cx: 36.36px;
  cy: 20.044px;
  r: 1.165px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ujjpp5h6w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.158 36.107c-2.665 3.38-5.7-2.33-5.658-4.801c.1-5.793 2.974-13.45 4.903-16.789a5.7 5.7 0 0 1 2.258-2.206a11.8 11.8 0 0 1 4.95-1.458c.567-.07 1.615 1.417 1.615 1.417h11.547s1.049-1.487 1.616-1.417a11.8 11.8 0 0 1 4.95 1.458a5.7 5.7 0 0 1 2.258 2.206c1.93 3.338 4.803 10.996 4.903 16.789c.042 2.472-2.993 8.182-5.658 4.801c-2.115-2.683-4.12-7.421-7.14-7.933a48.5 48.5 0 0 0-6.702-.35a50 50 0 0 0-6.702.35c-3.08.402-5.024 5.25-7.14 7.933");
}

.x8aggebjb {
  cx: 33.545px;
  cy: 17.232px;
  r: 1.165px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
