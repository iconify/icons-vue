<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="tmg8q67bk"/><path class="ckjei-2cv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:long-context" /></template>
<style>
.ckjei-2cv {
  d: path("M7.5 3.75v9.5m4.5-9.5v9.5m4.5-9.5v9.5m-13 5.25h17M6.25 15.75L3.5 18.5l2.75 2.75m11.5-5.5l2.75 2.75l-2.75 2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tmg8q67bk {
  width: 18.5px;
  height: 9.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 2.5px;
}

</style>
