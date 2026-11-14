<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omb60cbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bouldering-brush" /></template>
<style>
.omb60cbbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 9.5h13.5A2.25 2.25 0 0 1 21 11.75A2.25 2.25 0 0 1 18.75 14H5.25A2.25 2.25 0 0 1 3 11.75A2.25 2.25 0 0 1 5.25 9.5M9 14v3a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2v-3M5.5 5v4.5m3-4.5v4.5M12 5v4.5M15.5 5v4.5m3-4.5v4.5");
}

</style>
