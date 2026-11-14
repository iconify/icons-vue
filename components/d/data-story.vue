<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ecx1f1bsg"/><path class="i8mwmkh-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-story" /></template>
<style>
.ecx1f1bsg {
  d: path("M12 6.5c-2-1.5-5-2-9.5-2V18c4.5 0 7.5.5 9.5 2c2-1.5 5-2 9.5-2V4.5c-4.5 0-7.5.5-9.5 2m0 0V20M5.5 9l3.5.75M5.5 12.5l3.5.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i8mwmkh-x {
  d: path("m14.5 14.5l2-3.5l2 1.5");
}

</style>
