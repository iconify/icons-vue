<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="rjgnj9hur"/><rect class="vv0u9-ufy"/><path class="yau_dyb2c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cpu" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rjgnj9hur {
  width: 11.5px;
  height: 11.5px;
  x: 6.25px;
  y: 6.25px;
  rx: 2px;
}

.vv0u9-ufy {
  width: 5px;
  height: 5px;
  x: 9.5px;
  y: 9.5px;
  rx: 1px;
}

.yau_dyb2c {
  d: path("M9.5 2.75v3.5m5-3.5v3.5m-5 11.5v3.5m5-3.5v3.5M2.75 9.5h3.5m-3.5 5h3.5m11.5-5h3.5m-3.5 5h3.5");
}

</style>
