<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kegavxbtq"/><path class="is67kdbls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:calendar-event" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.is67kdbls {
  fill: currentColor;
  d: path("m12.5 11.625l.172.473a1.5 1.5 0 0 0 1.285.982l.623.052a.556.556 0 0 1 .295.993l-.354.275a1.5 1.5 0 0 0-.534 1.548l.143.572a.57.57 0 0 1-.88.605l-.39-.273a1.5 1.5 0 0 0-1.72 0l-.39.273a.57.57 0 0 1-.88-.605l.143-.572a1.5 1.5 0 0 0-.534-1.548l-.354-.275a.556.556 0 0 1 .295-.993l.623-.052a1.5 1.5 0 0 0 1.285-.982l.172-.473a.532.532 0 0 1 1 0");
}

.kegavxbtq {
  d: path("M7.375 3.5h9.25A4.375 4.375 0 0 1 21 7.875v9.25a4.375 4.375 0 0 1-4.375 4.375h-9.25A4.375 4.375 0 0 1 3 17.125v-9.25A4.375 4.375 0 0 1 7.375 3.5M8 2v2.75M16 2v2.75M3 7.5h18");
}

</style>
