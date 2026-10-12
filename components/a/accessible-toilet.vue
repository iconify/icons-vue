<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="sc1arcvlm"/><path class="gvq7syb7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:accessible-toilet" /></template>
<style>
.gvq7syb7p {
  d: path("M3.75 11.25h11.5c0 3-2 5-4.5 5.5l.75 4.5h-6l.75-4.5c-1.5-.75-2.5-2.75-2.5-5.5m16-3.5v9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sc1arcvlm {
  width: 5px;
  height: 5.25px;
  x: 3.75px;
  y: 2.75px;
  rx: 1.25px;
}

</style>
