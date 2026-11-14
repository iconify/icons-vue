<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp08r91oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:airspeed-indicator" /></template>
<style>
.xp08r91oo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0ZM6 15.5l-2.25 1.25M6 8.5L3.75 7.25M12 5V2.5m6 6l2.25-1.25M18 15.5l2.25 1.25M12 12l2.75-4.75M12 12h.01");
}

</style>
