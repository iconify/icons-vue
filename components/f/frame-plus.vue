<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u65952buc"/><rect class="iilnymbwy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:frame-plus" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iilnymbwy {
  width: 4px;
  height: 4px;
  x: 10px;
  y: 10px;
  rx: 1px;
}

.u65952buc {
  d: path("M7.25 3.75v16.5m9.5-16.5v16.5m-13-13h16.5m-16.5 9.5h16.5");
}

</style>
