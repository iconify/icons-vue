<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jz7d9wkha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bacterium-rod" /></template>
<style>
.jz7d9wkha {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.904 13.793l3.889-3.889a3.75 3.75 0 0 1 5.303 0a3.75 3.75 0 0 1 0 5.303l-3.889 3.889a3.75 3.75 0 0 1-5.303 0a3.75 3.75 0 0 1 0-5.303M14.25 9.75c2.25-.5.75-3 2.75-3.5s1-3 3-3.25c.75-.1 1.25 0 1.5-.5");
}

</style>
