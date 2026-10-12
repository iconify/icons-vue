<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zvljvpbav"/><rect class="oduqie_4v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:incense-stick" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oduqie_4v {
  width: 18.5px;
  height: 3px;
  x: 2.75px;
  y: 18.25px;
  rx: 1.5px;
}

.zvljvpbav {
  d: path("M15.5 8.25c1.5-.5 1.75-1.75 1-2.75s-.25-2.25 1.25-2.75m1 7.75c1.25-.25 2-1 2.25-2M7.5 18.25L14.75 9");
}

</style>
