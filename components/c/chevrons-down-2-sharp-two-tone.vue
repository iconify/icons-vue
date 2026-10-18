<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uevc8g7sc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevrons-down-2-sharp-two-tone" /></template>
<style>
.uevc8g7sc {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.7071 2.7071L12 8L17.2929 2.7071M6.7071 9.2071L12 14.5L17.2929 9.2071");
}

</style>
