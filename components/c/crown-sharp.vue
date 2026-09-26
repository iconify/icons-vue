<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gskaorbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:crown-sharp" /></template>
<style>
.gskaorbpq {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.5 20L2 6L7.5 11L12 4L16.5 11L22 6L20.5 20L3.5 20ZM2.9643 15L21.0357 15");
}

</style>
