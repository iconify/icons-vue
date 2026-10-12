<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="fr9wc8ere"/><circle class="xrii8hxli"/><path class="ryab5cbdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:image-filter" /></template>
<style>
.fr9wc8ere {
  width: 18.5px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ryab5cbdq {
  d: path("M12 7.25a4.75 4.75 0 0 0 0 9.5Z");
}

.xrii8hxli {
  cx: 12px;
  cy: 12px;
  r: 4.75px;
}

</style>
