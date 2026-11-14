<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hatt_ok2l"/><path class="tkrozcchq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:clay-pinch-pot" /></template>
<style>
.hatt_ok2l {
  d: path("M3 17.5c.5-8 4.5-11 9-11s8.5 3 9 11Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tkrozcchq {
  d: path("M8.5 12a3.5 2 0 1 0 7 0a3.5 2 0 1 0-7 0");
}

</style>
