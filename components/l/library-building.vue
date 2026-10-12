<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="qby_-fbag"/><path class="aajf_2b6b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:library-building" /></template>
<style>
.aajf_2b6b {
  d: path("M2.75 3.25h18.5M12 11v6.75M12 11c-1-.75-2.5-1-4-1v6.75c1.5 0 3 .25 4 1c1-.75 2.5-1 4-1V10c-1.5 0-3 .25-4 1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qby_-fbag {
  width: 17.5px;
  height: 15.25px;
  x: 3.25px;
  y: 6px;
  rx: 1.5px;
}

</style>
