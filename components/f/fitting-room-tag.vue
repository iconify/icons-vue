<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z-51d9bau"/><path class="ewhdvbb2q"/><path class="p5b2tsf9r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fitting-room-tag" /></template>
<style>
.ewhdvbb2q {
  d: path("M11 9.75a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p5b2tsf9r {
  d: path("M12 8.75V5c0-1.5 1.25-2.5 2.5-2.5s2.25 1 2 2.25m-6.75 8.5C10 12.5 10.75 12 12 12s2.25.6 2.25 1.75c0 1-.75 1.5-2 1.5c1.25 0 2.25.65 2.25 2c0 1-1 1.75-2.5 1.75c-1.25 0-2-.5-2.5-1.25");
}

.z-51d9bau {
  d: path("M9.5 7h5a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-5A3.5 3.5 0 0 1 6 18v-7.5A3.5 3.5 0 0 1 9.5 7");
}

</style>
