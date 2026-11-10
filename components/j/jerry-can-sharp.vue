<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd044ubxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:jerry-can-sharp" /></template>
<style>
.nd044ubxu {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.001 6V2H19.001V6M2.516 6.29L8.487 2.71M10.001 13V17M10.001 13H14.001M10.001 13L8.708 11.71M10.001 17H14.001M10.001 17L8.708 18.29M14.001 13V17M14.001 13L15.294 11.71M14.001 17L15.294 18.29M21.001 6V22H3.001V11L11.001 6H21.001Z");
}

</style>
