<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mg7x380wu"/><path class="hkhvpybkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cognitive" /></template>
<style>
.hkhvpybkt {
  d: path("M8.75 6.75h3.75L10.75 10h3l-5 5.75V11.5h-2.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mg7x380wu {
  d: path("M5.5 21.25V18c-1.75-1.5-2.75-3.75-2.75-6.5A7.25 7.25 0 0 1 10 4.25h.25a5.5 5.5 0 0 1 5.5 5.5l1.5 2.75l-1.5.75v2a2 2 0 0 1-2 2H12.5v4Z");
}

</style>
