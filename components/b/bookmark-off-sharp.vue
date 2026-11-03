<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nf5pmccce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bookmark-off-sharp" /></template>
<style>
.nf5pmccce {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 20L20 22L12 18.4223L4 22L4 4M6.6569 2L20 2L20 15.3431M1.7071 1.7071L22.2929 22.2929");
}

</style>
