<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iztepxbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:light-bulb-circuit" /></template>
<style>
.iztepxbjf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 16c0-2-3-3.5-3-7a6 6 0 0 1 12 0c0 3.5-3 5-3 7Zm.5 0v2.5a2 2 0 0 0 2 2h1a2 2 0 0 0 2-2V16M6 9H3.5V5M18 9h2.5V5m-17 0h.01M20.5 5h.01");
}

</style>
