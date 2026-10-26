<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igbf_dbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:construction-sharp" /></template>
<style>
.igbf_dbqo {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 4L22 4L22 11L2 11ZM5.5 11L12.5 4M11.5 11L18.5 4M6 11L6 20M18 11L18 20M3 20L9 20M15 20L21 20");
}

</style>
