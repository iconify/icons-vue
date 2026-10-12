<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fkqnxybkw"/><rect class="g2dkuobet"/><path class="gcalxb98a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ballot" /></template>
<style>
.fkqnxybkw {
  d: path("M8.75 5L11 7.25l4.25-4.5");
}

.g2dkuobet {
  width: 16.5px;
  height: 11px;
  x: 3.75px;
  y: 10.25px;
  rx: 2px;
}

.gcalxb98a {
  d: path("M8 13h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
