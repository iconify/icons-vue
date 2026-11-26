<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="deutbrbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:diamonds-sharp" /></template>
<style>
.deutbrbor {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 5L22 12L15 19L8 12L15 5ZM9.8787 5.8787L9 5L2 12L9 19L9.8787 18.1213");
}

</style>
