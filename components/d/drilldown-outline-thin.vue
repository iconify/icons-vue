<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k6nj2fbya"/><path class="cbvfl-_0s"/><path class="f0zlw3bmh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:drilldown-outline-thin" /></template>
<style>
.cbvfl-_0s {
  d: path("M6 9v4h15");
}

.f0zlw3bmh {
  d: path("M10 15v4h11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6nj2fbya {
  d: path("M3 5h18");
}

</style>
