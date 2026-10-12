<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bcigp9a4c"/><path class="z9g08dbag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arrow-step-up" /></template>
<style>
.bcigp9a4c {
  d: path("M3.75 20.25h5v-5h5v-5h3.5V4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z9g08dbag {
  d: path("m14.25 7.5l3-3l3 3");
}

</style>
