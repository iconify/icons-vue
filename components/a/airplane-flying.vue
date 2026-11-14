<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa4eelbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:airplane-flying" /></template>
<style>
.oa4eelbbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5c1 0 1.5 1 1.5 2V10l7.5 4.5v2l-7.5-2v4L16 20v1.5l-4-1l-4 1V20l2.5-1.5v-4l-7.5 2v-2l7.5-4.5V5.5c0-1 .5-2 1.5-2");
}

</style>
