<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wprpkcche"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baseball-batter" /></template>
<style>
.wprpkcche {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 7a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM2.5 21.5c0-4 3-7.5 7-7.5s7 3.5 7 7.5M14 14.25l1 .5l7-11l-3-1.5Z");
}

</style>
