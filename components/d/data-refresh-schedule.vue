<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p1wg01bwy"/><path class="w36328sup"/><path class="f9x9olbpi"/><path class="x53cqrb1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-refresh-schedule" /></template>
<style>
.f9x9olbpi {
  d: path("m18.5 21l-2.5-.5l1-2.5m-8.909 2.383a9.25 9.25 0 0 1 0-16.766");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p1wg01bwy {
  d: path("M9.75 8.5h4.5A1.75 1.75 0 0 1 16 10.25v4A1.75 1.75 0 0 1 14.25 16h-4.5A1.75 1.75 0 0 1 8 14.25v-4A1.75 1.75 0 0 1 9.75 8.5M8 11h8m-5.5-3.5v2m3-2v2");
}

.w36328sup {
  d: path("M15.909 3.617a9.25 9.25 0 0 1 0 16.766");
}

.x53cqrb1p {
  d: path("m5.5 3l2.5.5L7 6");
}

</style>
