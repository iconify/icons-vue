<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="lm_nqrb4o"/><path class="iyz0sdbbh"/><rect class="c3r4r5bgi"/><path class="u1a3vo70f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:keyboard-tray" /></template>
<style>
.c3r4r5bgi {
  width: 10.5px;
  height: 6.5px;
  x: 6.75px;
  y: 13.75px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iyz0sdbbh {
  d: path("M4.25 7.25v13m15.5-13v13m-17 0h18.5");
}

.lm_nqrb4o {
  width: 18.5px;
  height: 4px;
  x: 2.75px;
  y: 3.25px;
  rx: 1.5px;
}

.u1a3vo70f {
  d: path("M9.25 17h5.5");
}

</style>
