<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s3g9dpavf"/><path class="v5r2tb21h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cocoa-bean" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s3g9dpavf {
  d: path("M12 2.5c4.75 3.5 4.75 15.5 0 19C7.25 18 7.25 6 12 2.5");
}

.v5r2tb21h {
  d: path("M10.25 7c-.5 3-.5 7 0 10m3.5-10c.5 3 .5 7 0 10");
}

</style>
