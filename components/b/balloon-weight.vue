<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ypavmybup"/><path class="f30n5ccig"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:balloon-weight" /></template>
<style>
.f30n5ccig {
  d: path("M12 13.5c-1.5 1.5 1.5 3 0 4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ypavmybup {
  d: path("M12 13.5c-4 0-5.5-3.5-5.5-6c0-3 2.5-5 5.5-5s5.5 2 5.5 5c0 2.5-1.5 6-5.5 6m-3.875 6.25l.269-.755A1.5 1.5 0 0 1 9.807 18h4.386a1.5 1.5 0 0 1 1.413.995l.269.755a1.31 1.31 0 0 1-1.233 1.75H9.358a1.31 1.31 0 0 1-1.233-1.75");
}

</style>
