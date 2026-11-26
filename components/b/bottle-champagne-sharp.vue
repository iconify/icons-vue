<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyryftk3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bottle-champagne-sharp" /></template>
<style>
.dyryftk3g {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 15L11 15M18 16C19.1046 16 21 14.2091 21 12L21 6L15 6L15 12C15 14.2091 16.8954 16 18 16ZM18 16L18 22M9 5L5 5L5 2L9 2ZM8.5 5L8.5 6.5C8.5 8.5 11 9.5 11 12L11 15L11 22L3 22L3 15L3 12C3 9.5 5.5 8.5 5.5 6.5L5.5 5M14 22L15 22L18 22L22 22");
}

</style>
