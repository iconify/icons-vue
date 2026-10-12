<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q6gk-kbhq"/><path class="xyaggacsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:api-plug" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q6gk-kbhq {
  d: path("M7.75 7.25h8.5A1.25 1.25 0 0 1 17.5 8.5V11a5.5 5.5 0 0 1-11 0V8.5a1.25 1.25 0 0 1 1.25-1.25m1.75-4.5v4.5m5-4.5v4.5");
}

.xyaggacsf {
  d: path("M12 16.5v1.75a3 3 0 0 0 3 3h2.25m-7-10h3.5");
}

</style>
