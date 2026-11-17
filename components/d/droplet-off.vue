<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyoug04yb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:droplet-off" /></template>
<style>
.uyoug04yb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 14c0-6-7-11-7-11s-.954.681-2.157 1.843M7.079 8.079C5.913 9.797 5 11.833 5 14a7 7 0 0 0 12.425 4.425M2 3l19 19");
}

</style>
