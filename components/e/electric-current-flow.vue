<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytp4nhbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:electric-current-flow" /></template>
<style>
.ytp4nhbgg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.723 5.346L4.952 10.06a1.502 1.502 0 0 0 1.173 2.44h1.177a1.75 1.75 0 0 1 1.741 1.936L8.875 16a1.051 1.051 0 0 0 1.858.779l3.785-4.613a1.478 1.478 0 0 0-1.143-2.416H12.19a1.75 1.75 0 0 1-1.74-1.93l.175-1.695a1.071 1.071 0 0 0-1.902-.779M14.5 18h7m-3-3l3 3l-3 3");
}

</style>
