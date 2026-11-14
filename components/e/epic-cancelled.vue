<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtpmlhdjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:epic-cancelled" /></template>
<style>
.rtpmlhdjf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.413 14.692L16.25 9.5h-6.5l1.5-7l-8.5 10h6.5L7.75 21l3.949-5.343M15.5 15.5l5 5m0-5l-5 5");
}

</style>
