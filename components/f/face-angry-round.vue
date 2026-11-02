<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynysorbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:face-angry-round" /></template>
<style>
.ynysorbju {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 0 0-18 0m5-3l2 1m6-1l-2 1m-6 5a5.657 5.657 0 0 1 8 0");
}

</style>
