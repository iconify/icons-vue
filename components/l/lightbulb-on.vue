<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad_yaubju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lightbulb-on" /></template>
<style>
.ad_yaubju {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 15.5a5 5 0 1 1 6 0V18H9Zm1 5.25h4M12 2v1.75M4.5 5L6 6.5M19.5 5L18 6.5");
}

</style>
