<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rv7s0bczy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:crane-sharp" /></template>
<style>
.rv7s0bczy {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 7L3 7L21 7L22 7M8 2L8 3L8 21M4 21L5 21L11 21L12 21M4 7L4 10L4 11M19 7L19 11M17 16L17 15L17 13C17 11.8954 17.8954 11 19 11C20.1046 11 21 11.8954 21 13L21 15L21 16");
}

</style>
