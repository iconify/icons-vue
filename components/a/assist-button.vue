<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dnp2npbye"/><circle class="fq1tmw63v"/><path class="hboedzb0t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:assist-button" /></template>
<style>
.dnp2npbye {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 2.5px;
}

.fq1tmw63v {
  cx: 12px;
  cy: 10.5px;
  r: 4px;
}

.hboedzb0t {
  d: path("M9 17.75h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
