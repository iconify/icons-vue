<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="zam6l9bxy"/><path class="q3gvemg1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:booster-landing" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q3gvemg1h {
  d: path("M9.75 5h-1.5m6 0h1.5m-6 6.5l-3.25 5m7.75-5l3.25 5M3.75 21.25h16.5M12 14.75c1.75 1.5 2 3 0 4.75c-2-1.75-1.75-3.25 0-4.75");
}

.zam6l9bxy {
  width: 4.5px;
  height: 12px;
  x: 9.75px;
  y: 2.75px;
  rx: 1.25px;
}

</style>
