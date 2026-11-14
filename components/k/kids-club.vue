<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fkc0odbok"/><path class="ptp4d6kht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kids-club" /></template>
<style>
.fkc0odbok {
  d: path("M7.75 9.5h6A2.25 2.25 0 0 1 16 11.75A2.25 2.25 0 0 1 13.75 14h-6a2.25 2.25 0 0 1-2.25-2.25A2.25 2.25 0 0 1 7.75 9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ptp4d6kht {
  d: path("m14.5 10l2-5.5h3l2 3.5l-2.75.5l-1.75 4M7.5 14l-1 4.25M14 14l1 4.25M2.5 17c4.5 4 12.5 4.25 18-.25M6 11.25l-3 2.5");
}

</style>
