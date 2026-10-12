<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="q2j9owbjj"/><rect class="j8tytbbff"/><path class="y_amm84ko"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:conditioner" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j8tytbbff {
  width: 8.5px;
  height: 12.75px;
  x: 3.75px;
  y: 8.5px;
  rx: 2.5px;
}

.q2j9owbjj {
  width: 5px;
  height: 2.75px;
  x: 5.5px;
  y: 2.75px;
  rx: 1px;
}

.y_amm84ko {
  d: path("M17.75 4.75c2.5 2.5 2.5 4.5 0 7s-2.5 4.5 0 7");
}

</style>
