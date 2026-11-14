<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dtjrp_bfl"/><path class="mzdlqyw0t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coat-check" /></template>
<style>
.dtjrp_bfl {
  d: path("M4 3h16m-8 0v3m0 0L7.5 7.5L5 21h14L16.5 7.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mzdlqyw0t {
  d: path("m9 7l3 5l3-5m-3 5v9");
}

</style>
