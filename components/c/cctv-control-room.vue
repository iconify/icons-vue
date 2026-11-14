<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewm67ccnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cctv-control-room" /></template>
<style>
.ewm67ccnn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 3h3.5A1.75 1.75 0 0 1 10 4.75v1.5A1.75 1.75 0 0 1 8.25 8h-3.5A1.75 1.75 0 0 1 3 6.25v-1.5A1.75 1.75 0 0 1 4.75 3m11 0h3.5A1.75 1.75 0 0 1 21 4.75v1.5A1.75 1.75 0 0 1 19.25 8h-3.5A1.75 1.75 0 0 1 14 6.25v-1.5A1.75 1.75 0 0 1 15.75 3m-11 7.75h3.5A1.75 1.75 0 0 1 10 12.5V14a1.75 1.75 0 0 1-1.75 1.75h-3.5A1.75 1.75 0 0 1 3 14v-1.5a1.75 1.75 0 0 1 1.75-1.75m11 0h3.5A1.75 1.75 0 0 1 21 12.5V14a1.75 1.75 0 0 1-1.75 1.75h-3.5A1.75 1.75 0 0 1 14 14v-1.5a1.75 1.75 0 0 1 1.75-1.75M3.5 21.5V19h17v2.5");
}

</style>
