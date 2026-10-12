<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hn6405w6q"/><rect class="yfr-i2jjg"/><path class="ae0h5kb0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:backpack-travel" /></template>
<style>
.ae0h5kb0o {
  d: path("M9 15h6");
}

.hn6405w6q {
  d: path("M9.25 7.25a2.75 2.75 0 0 1 5.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yfr-i2jjg {
  width: 13.5px;
  height: 14px;
  x: 5.25px;
  y: 7.25px;
  rx: 3px;
}

</style>
