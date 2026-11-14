<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-hswgb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flag-checkered" /></template>
<style>
.y-hswgb5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 4h10.5A1.75 1.75 0 0 1 19 5.75v6.5A1.75 1.75 0 0 1 17.25 14H6.75A1.75 1.75 0 0 1 5 12.25v-6.5A1.75 1.75 0 0 1 6.75 4M12 4v10M5 9h14M5 3v18");
}

</style>
