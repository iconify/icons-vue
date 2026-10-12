<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="em3h44bre"/><path class="feftjkvvi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hospital-clock" /></template>
<style>
.em3h44bre {
  d: path("M3.75 21.25V12.5a1.5 1.5 0 0 1 1.5-1.5H7V4.75a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2V11h1.75a1.5 1.5 0 0 1 1.5 1.5v8.75ZM12 5.5V10M9.75 7.75h4.5");
}

.feftjkvvi {
  d: path("M10.25 21.25v-2.5a1.75 1.75 0 0 1 3.5 0v2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
