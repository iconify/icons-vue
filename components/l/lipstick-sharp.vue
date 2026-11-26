<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m23tc_fee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lipstick-sharp" /></template>
<style>
.m23tc_fee {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 14L16 5.385L8 2.0013L8 15L6 15L6 22L18 22L18 15L16 15ZM16 11L8 11");
}

</style>
