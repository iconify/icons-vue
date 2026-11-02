<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sca4vgbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gavel-sharp" /></template>
<style>
.sca4vgbly {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m14 3l7 7l-4 4l-7-7zm-1 17h8m-6-8l-8 8a2.121 2.121 0 1 1-3-3l8-8");
}

</style>
