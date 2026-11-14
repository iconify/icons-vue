<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kr6grkbdu"/><path class="j6x-68b9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:defence-shield" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j6x-68b9v {
  d: path("m12.5 8.625l.172.473a1.5 1.5 0 0 0 1.285.982l.623.052a.556.556 0 0 1 .295.993l-.354.275a1.5 1.5 0 0 0-.534 1.548l.143.572a.57.57 0 0 1-.88.605l-.39-.273a1.5 1.5 0 0 0-1.72 0l-.39.273a.57.57 0 0 1-.88-.605l.143-.572a1.5 1.5 0 0 0-.534-1.548l-.354-.275a.556.556 0 0 1 .295-.993l.623-.052a1.5 1.5 0 0 0 1.285-.982l.172-.473a.532.532 0 0 1 1 0");
}

.kr6grkbdu {
  d: path("m12 2.5l7.5 3V11c0 5-3.5 8.5-7.5 10.5c-4-2-7.5-5.5-7.5-10.5V5.5Z");
}

</style>
