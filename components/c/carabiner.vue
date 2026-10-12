<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xclszn5fv"/><rect class="huovvtbud"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:carabiner" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.huovvtbud {
  width: 2.5px;
  height: 4px;
  x: 15.25px;
  y: 13px;
  rx: 0.75px;
}

.xclszn5fv {
  d: path("M16.5 7.75c0-3-2.5-5-5.5-5h-.5a3 3 0 0 0-3 3v12.5a3 3 0 0 0 3 3h.5c2.75 0 5.5-1.5 5.5-4.25m0-4v-2.25");
}

</style>
