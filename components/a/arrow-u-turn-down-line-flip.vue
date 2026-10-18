<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8p1n65-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-u-turn-down-line-flip" /></template>
<style>
.l8p1n65-t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 14L19 12C19 9.2386 16.7614 7 14 7C11.2386 7 9 9.2386 9 12L9 20M5 16L8.6096 20.8123C8.8097 21.0625 9.1903 21.0625 9.3904 20.8123L13 16M4 3L20 3");
}

</style>
