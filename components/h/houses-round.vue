<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ww22mq7_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:houses-round" /></template>
<style>
.ww22mq7_d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 21h8m-8 0H3v-5.81a4 4 0 0 1 1.366-3.01l1.134-.992a3.796 3.796 0 0 1 5 0l1.134.992A4 4 0 0 1 13 15.19zm0-14h.01M17 7h.01M17 11h.01M17 15h.01M9 9.875V3h8a4 4 0 0 1 4 4v14");
}

</style>
