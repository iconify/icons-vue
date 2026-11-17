<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r39j4wb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:blinds-round" /></template>
<style>
.r39j4wb1h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h18M5 3v10a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V3M5 7h14M5 11h14m-7 4v2m-2 2a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
