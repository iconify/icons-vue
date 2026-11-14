<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igg-uwwcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drum-key" /></template>
<style>
.igg-uwwcj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 3h13.5A2.25 2.25 0 0 1 21 5.25a2.25 2.25 0 0 1-2.25 2.25H5.25A2.25 2.25 0 0 1 3 5.25A2.25 2.25 0 0 1 5.25 3M12 7.5V15m-1.312 0h2.625a2.19 2.19 0 0 1 2.187 2.188v2.125a2.19 2.19 0 0 1-2.187 2.187h-2.625A2.19 2.19 0 0 1 8.5 19.313v-2.125A2.19 2.19 0 0 1 10.688 15");
}

</style>
