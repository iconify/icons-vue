<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="meaesfbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-clock-corner-round" /></template>
<style>
.meaesfbvn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 21H8a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4M8 3v2m8-2v2M4 9h16m-9 8a5 5 0 1 0 10 0a5 5 0 0 0-10 0m5-2v2h2");
}

</style>
