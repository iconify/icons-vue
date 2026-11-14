<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th1-p2c2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:filing-cabinet" /></template>
<style>
.th1-p2c2o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 7h12.75A2.625 2.625 0 0 1 21 9.625v1.75A2.625 2.625 0 0 1 18.375 14H5.625A2.625 2.625 0 0 1 3 11.375v-1.75A2.625 2.625 0 0 1 5.625 7M4.5 14v5.5a2 2 0 0 0 2 2h11a2 2 0 0 0 2-2V14m-13-7V3.5h11V7M10 10.5h4m-4 7.25h4");
}

</style>
