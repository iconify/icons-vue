<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcqmokbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layers-2-sharp" /></template>
<style>
.pcqmokbkn {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.182 12L2 16.5L12 22L22 16.5L13.818 12M12 2L22 7.5L12 13L2 7.5L12 2Z");
}

</style>
