<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="vp548fpje"/><rect class="ul3x_25kb"/><rect class="w2hhqos4y"/><rect class="j3r_gbb_c"/><rect class="funz83vki"/><rect class="ocsx9yn_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-bar-stacked" /></template>
<style>
.funz83vki {
  width: 3.5px;
  height: 4px;
  x: 16.75px;
  y: 16.25px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j3r_gbb_c {
  width: 3.5px;
  height: 4px;
  x: 10.25px;
  y: 3.75px;
  rx: 1px;
}

.ocsx9yn_m {
  width: 3.5px;
  height: 4px;
  x: 16.75px;
  y: 9.25px;
  rx: 1px;
}

.ul3x_25kb {
  width: 3.5px;
  height: 3.5px;
  x: 3.75px;
  y: 8.25px;
  rx: 1px;
}

.vp548fpje {
  width: 3.5px;
  height: 5.5px;
  x: 3.75px;
  y: 14.75px;
  rx: 1px;
}

.w2hhqos4y {
  width: 3.5px;
  height: 9.5px;
  x: 10.25px;
  y: 10.75px;
  rx: 1px;
}

</style>
