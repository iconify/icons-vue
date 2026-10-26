<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbtrtx6fe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:factory-sharp" /></template>
<style>
.qbtrtx6fe {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 21L2 3L7 3L7 11L12 8L12 11L17 8L17 11L22 8L22 21ZM2 7L7 7M11 5.5L11 3L23 3M10 14L10 18M14 14L14 18M18 14L18 18");
}

</style>
