<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bckix3qhv"/><path class="uy514mbsq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cold-frame" /></template>
<style>
.bckix3qhv {
  d: path("M3.5 19.5v-14l17 5.5v8.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uy514mbsq {
  d: path("M12 19.5v-4.25m0 .75c0-2.5-2-4-4.5-4c0 2.5 2 4 4.5 4m0-.75c0-2 1.75-3 3.75-3c0 2.25-1.5 3-3.75 3");
}

</style>
