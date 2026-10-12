<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g0m5krttq"/><rect class="ze4r7hc3g"/><rect class="a4htvjspk"/><path class="ugvz7ebru"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baby-monitor" /></template>
<style>
.a4htvjspk {
  width: 6.5px;
  height: 5px;
  x: 8.75px;
  y: 9.75px;
  rx: 1px;
}

.g0m5krttq {
  d: path("M15 7.25v-4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ugvz7ebru {
  d: path("M10 18h4");
}

.ze4r7hc3g {
  width: 11.5px;
  height: 14px;
  x: 6.25px;
  y: 7.25px;
  rx: 2.5px;
}

</style>
