<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="a-7h14mtq"/><path class="y6atf0hej"/><circle class="og3k95x3a"/><path class="u4qq3nbez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:height-rod" /></template>
<style>
.a-7h14mtq {
  width: 3px;
  height: 18.5px;
  x: 13.5px;
  y: 2.75px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.og3k95x3a {
  cx: 7px;
  cy: 9px;
  r: 2px;
}

.u4qq3nbez {
  d: path("M3.5 21.25v-4.5a3.5 3.5 0 0 1 7 0v4.5Zm0 0h17M4.5 7h9");
}

.y6atf0hej {
  d: path("M13.5 9.5H15M13.5 13h1m-1 3.5H15");
}

</style>
