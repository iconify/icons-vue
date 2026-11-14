<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hqraw75ys"/><path class="m3odcu4in"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:badminton-shuttle-flight" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hqraw75ys {
  d: path("m16.289 6.789l.922.922a1.5 1.5 0 0 1 .26 1.772l-2.015 3.742a1.5 1.5 0 0 1-2.382.349l-2.648-2.648a1.5 1.5 0 0 1 .349-2.382l3.742-2.015a1.5 1.5 0 0 1 1.772.26");
}

.m3odcu4in {
  d: path("M16 5.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M3 17l3.5-3.5M7 21l3.5-3.5");
}

</style>
