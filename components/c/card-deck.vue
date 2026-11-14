<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mmafhq1gn"/><path class="wltkv2d_v"/><path class="befzneb4m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:card-deck" /></template>
<style>
.befzneb4m {
  d: path("M10 4.75V3.5A1.5 1.5 0 0 1 11.5 2H19a1.5 1.5 0 0 1 1.5 1.5v11A1.5 1.5 0 0 1 19 16h-1.5m-7.125-3.25l.604.939a1.5 1.5 0 0 1 0 1.622l-.604.939a1.337 1.337 0 0 1-2.25 0l-.604-.939a1.5 1.5 0 0 1 0-1.622l.604-.939a1.337 1.337 0 0 1 2.25 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mmafhq1gn {
  d: path("M6.625 7.5h5.25a2.625 2.625 0 0 1 2.625 2.625v8.75a2.625 2.625 0 0 1-2.625 2.625h-5.25A2.625 2.625 0 0 1 4 18.875v-8.75A2.625 2.625 0 0 1 6.625 7.5");
}

.wltkv2d_v {
  d: path("M7 7.5V6.25a1.5 1.5 0 0 1 1.5-1.5H16a1.5 1.5 0 0 1 1.5 1.5v11a1.5 1.5 0 0 1-1.5 1.5h-1.5");
}

</style>
