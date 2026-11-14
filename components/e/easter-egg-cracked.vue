<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w9yptdbrh"/><path class="la0o9c8uc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:easter-egg-cracked" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.la0o9c8uc {
  d: path("m5 14l2.75-2.5l2.5 4l2.75-4l2.75 4L19 14");
}

.w9yptdbrh {
  d: path("M12 2.5c4.5 0 7 7 7 11.5s-3 7.5-7 7.5s-7-3-7-7.5S7.5 2.5 12 2.5");
}

</style>
