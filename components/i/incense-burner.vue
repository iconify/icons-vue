<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="thwqz4b4l"/><rect class="auv4cqxpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:incense-burner" /></template>
<style>
.auv4cqxpi {
  width: 7.5px;
  height: 2.25px;
  x: 8.25px;
  y: 19px;
  rx: 0.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.thwqz4b4l {
  d: path("M12 12V9.25C11 8 13 7 12 6s1-2 0-3.25M8.75 11V9.5c-.75-.9.75-1.6 0-2.5m6.5 4V9.5c-.75-.9.75-1.6 0-2.5M6.5 12h11a5.5 4.5 0 0 1-11 0");
}

</style>
