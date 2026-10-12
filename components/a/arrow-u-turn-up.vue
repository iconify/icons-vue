<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zpotb2bui"/><path class="zun_w-eha"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arrow-u-turn-up" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zpotb2bui {
  d: path("M5.5 3.75v11a4.75 4.75 0 0 0 9.5 0V4.25");
}

.zun_w-eha {
  d: path("M11.5 7.5L15 4l3.5 3.5");
}

</style>
