<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="aop1edb8h"/><path class="dtnajob5t"/><circle class="ku1tp5bhm"/><path class="bxqbg5bwm"/><circle class="yrmwkhkks"/><path class="kfbno2boj"/><path class="m_qu4cngo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:japanese-tv" /></template>
<style>
.aop1edb8h {
  width: 39px;
  height: 23.582px;
  x: 4.5px;
  y: 16.185px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.162px;
  ry: 5.162px;
}

.bxqbg5bwm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.774 16.185l-3.023-5.996");
}

.dtnajob5t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.226 16.185l3.023-5.996");
}

.kfbno2boj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.524 24.162h6.306m-7.651 3.14h8.996m-4.498 0c0 3.014-.296 4.017-2.357 5.52m10.739-8.66v8.313c2.41 0 6.112-1.976 7.247-4.156m3.547-4.157V31.2c0 .87.477 1.388 3.519 1.388c1.822 0 3.168-.336 3.168-.336");
}

.ku1tp5bhm {
  cx: 29.728px;
  cy: 9.234px;
  r: 1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m_qu4cngo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.853 25.998c-2.776 1.164-6 1.837-6 1.837m5.96-4.244l.641 1.051m.726-1.602l.641 1.051");
}

.yrmwkhkks {
  cx: 18.272px;
  cy: 9.234px;
  r: 1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
