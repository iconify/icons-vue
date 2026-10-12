<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cp3oo4dcj"/><rect class="b9s4y5bum"/><path class="jtnrz8b1y"/><rect class="ixnr5t1dz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chhatri" /></template>
<style>
.b9s4y5bum {
  width: 17px;
  height: 2.5px;
  x: 3.5px;
  y: 10px;
  rx: 0.75px;
}

.cp3oo4dcj {
  d: path("M12 2.75v1.5M5.5 10a6.5 5.75 0 0 1 13 0Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ixnr5t1dz {
  width: 18px;
  height: 2.5px;
  x: 3px;
  y: 18.75px;
  rx: 0.75px;
}

.jtnrz8b1y {
  d: path("M6 12.5v6.25m4-6.25v6.25m4-6.25v6.25m4-6.25v6.25");
}

</style>
