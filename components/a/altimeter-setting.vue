<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ybpin5e7w"/><path class="lqp75bc3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:altimeter-setting" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lqp75bc3q {
  d: path("M12 18.5za1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5M7.25 7.75L5 6.5M12 5V2.5m4.75 5.25L19 6.5m-7 4L10 7m2 3.5h.01");
}

.ybpin5e7w {
  d: path("M4 10.5a8 8 0 1 0 16 0a8 8 0 1 0-16 0");
}

</style>
