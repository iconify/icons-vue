<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="lgmzjf4_y"/><rect class="zbhd3ibvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:layout-tablet-split" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lgmzjf4_y {
  width: 7.75px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 2px;
}

.zbhd3ibvz {
  width: 7.75px;
  height: 16.5px;
  x: 13.5px;
  y: 3.75px;
  rx: 2px;
}

</style>
