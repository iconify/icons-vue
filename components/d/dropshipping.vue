<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wdogs1kfo"/><rect class="yn62lec3a"/><path class="r3_t4vbly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dropshipping" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r3_t4vbly {
  d: path("M10.75 13.75v3");
}

.wdogs1kfo {
  d: path("M3 11.25a7.75 7.75 0 0 1 15.5 0M16.25 9l2.25 2.25L20.75 9");
}

.yn62lec3a {
  width: 8.5px;
  height: 7.5px;
  x: 6.5px;
  y: 13.75px;
  rx: 1.5px;
}

</style>
