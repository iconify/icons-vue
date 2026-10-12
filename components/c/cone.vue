<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="spb0rwbnx"/><path class="bjacox7xx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cone" /></template>
<style>
.bjacox7xx {
  d: path("M4.25 17.5a8.5 3 0 0 1 15.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.spb0rwbnx {
  d: path("M10.9 3.6c.5-.9 1.7-.9 2.2 0L20.5 18a8.5 3.25 0 0 1-17 0Z");
}

</style>
