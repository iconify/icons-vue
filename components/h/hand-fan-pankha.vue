<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vghh_1b0g"/><path class="k3nhh1-fh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hand-fan-pankha" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k3nhh1-fh {
  d: path("M9.5 13.9L12 11l2.5 2.9m-2.5.35v7");
}

.vghh_1b0g {
  d: path("M12 14.25c-4.5 0-7.25-2.25-7.25-5.75S7.5 2.75 12 2.75S19.25 5 19.25 8.5S16.5 14.25 12 14.25");
}

</style>
