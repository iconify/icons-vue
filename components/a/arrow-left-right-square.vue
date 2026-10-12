<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="t0jrdmbrp"/><path class="rpiz0hb3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arrow-left-right-square" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rpiz0hb3i {
  d: path("M16.5 12H7.75m3.75 3.75L7.75 12l3.75-3.75");
}

.t0jrdmbrp {
  width: 17.5px;
  height: 17.5px;
  x: 3.25px;
  y: 3.25px;
  rx: 4px;
}

</style>
