<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gdk0rpb7p"/><path class="o54qvsbqq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:desert-sun" /></template>
<style>
.gdk0rpb7p {
  d: path("M9.5 9.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-7 9Q9 13 15.5 18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o54qvsbqq {
  d: path("M10.5 21q5.5-5.5 11-1.5M12 4.25V2.5m5.25 7H19m-12.25 0H5m3.25-3.75L7 4.5m8.75 1.25L17 4.5");
}

</style>
