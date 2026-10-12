<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="x00qgzx7x"/><path class="nytt4lz9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:constitution-article" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nytt4lz9q {
  d: path("M10.25 6.25h3.5m-1.75 0v5m-1.75 0h3.5m-5.5 3.5h7.5m-7.5 3h5");
}

.x00qgzx7x {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
