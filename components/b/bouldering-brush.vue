<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7l6zh_9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bouldering-brush" /></template>
<style>
.h7l6zh_9q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9.5h18V14H3ZM9 14v3a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2v-3M5.5 5v4.5m3-4.5v4.5M12 5v4.5M15.5 5v4.5m3-4.5v4.5");
}

</style>
