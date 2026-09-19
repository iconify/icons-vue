<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="diln8abku"/><rect class="tg9uaed0y"/><rect class="i5bsim0rg"/><rect class="b-9ok1csu"/><rect class="q1qr0ub3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:keks-pay" /></template>
<style>
.b-9ok1csu {
  width: 18.5px;
  height: 18.5px;
  x: 24px;
  y: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.diln8abku {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.75 5.5v5.864m0 6.772V24M24 14.364h-6.25m-3 9.636v5.864m0 6.772V42.5M24 32.864h-6.25m15.5 3.818H24m18.5-7.25h-9.25m9.25-11.057h-9.25m9.25-7.25h-9.25");
}

.i5bsim0rg {
  width: 18.5px;
  height: 18.5px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.q1qr0ub3b {
  width: 18.5px;
  height: 18.5px;
  x: 24px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.tg9uaed0y {
  width: 18.5px;
  height: 18.5px;
  x: 5.5px;
  y: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

</style>
