<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc5rukbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-arrow-down-sharp" /></template>
<style>
.wc5rukbej {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 20L2 20L2 4L22 4L22 11M2 7L11.2929 11C11.7154 11.2817 12.2846 11.2817 12.7071 11L22 7M19 13L19 20M15.7071 16.7071L19 20L22.2929 16.7071");
}

</style>
