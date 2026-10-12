<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wokmn_bns"/><rect class="btd8wybus"/><path class="tcthxf__q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:breast-pump" /></template>
<style>
.btd8wybus {
  width: 6.5px;
  height: 12.75px;
  x: 9.75px;
  y: 8.5px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tcthxf__q {
  d: path("M9.75 12.5h6.5M13 8.5V6.25a2.5 2.5 0 0 1 2.5-2.5h4.75");
}

.wokmn_bns {
  d: path("M6.27 10.39L3.23 8.11q-.48-.36-.48.24v7.3q0 .6.48.24l3.04-2.28q.48-.36.48-.96v-1.3q0-.6-.48-.96");
}

</style>
