<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gsnxmxbsj"/><path class="rvpuqt4rh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gin-and-tonic" /></template>
<style>
.gsnxmxbsj {
  d: path("M5.867 6h7.266a1.75 1.75 0 0 1 1.747 1.863l-.774 12a1.75 1.75 0 0 1-1.747 1.637H6.641a1.75 1.75 0 0 1-1.747-1.637l-.774-12A1.75 1.75 0 0 1 5.867 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rvpuqt4rh {
  d: path("M12 6a4 4 0 0 1 8 0Zm4 0V2.5M6 11h7.5");
}

</style>
