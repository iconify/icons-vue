<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmmd7vbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:braces-sharp-two-tone" /></template>
<style>
.fmmd7vbqa {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 2L6 2L6 10L4 12L6 14L6 22L9 22M15 2L18 2L18 10L20 12L18 14L18 22L15 22");
}

</style>
