<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f50th2j6r"/><path class="w1v5_0ggf"/><path class="b4f-a4rvb"/><path class="ut_f-ny8k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:envelope-stack" /></template>
<style>
.b4f-a4rvb {
  d: path("M8 6.75V5.5A1.5 1.5 0 0 1 9.5 4H20a1.5 1.5 0 0 1 1.5 1.5v9h-2.75");
}

.f50th2j6r {
  d: path("M6 9.5h6.5A3.5 3.5 0 0 1 16 13v3.5a3.5 3.5 0 0 1-3.5 3.5H6a3.5 3.5 0 0 1-3.5-3.5V13A3.5 3.5 0 0 1 6 9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ut_f-ny8k {
  d: path("m3 11l6.25 4.25L15.5 11");
}

.w1v5_0ggf {
  d: path("M5.25 9.5V8.25a1.5 1.5 0 0 1 1.5-1.5h10.5a1.5 1.5 0 0 1 1.5 1.5v9H16");
}

</style>
