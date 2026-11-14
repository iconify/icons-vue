<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjw2evbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kart-track" /></template>
<style>
.cjw2evbqn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3.5h10A3.5 3.5 0 0 1 19.5 7v10a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 17v-1.5A1.5 1.5 0 0 1 4 14h7.5a2 2 0 0 0 0-4H4a1.5 1.5 0 0 1-1.5-1.5V7A3.5 3.5 0 0 1 6 3.5M17.5 12h4");
}

</style>
