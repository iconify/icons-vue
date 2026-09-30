<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_qzw7byj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gold-bars-sharp" /></template>
<style>
.r_qzw7byj {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 10L9.5 4L14.5 4L16 10L8 10ZM2 20L3.5 14L8.5 14L10 20L2 20ZM14 20L15.5 14L20.5 14L22 20L14 20Z");
}

</style>
