<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfiap0cip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flip-2-horizontal-sharp" /></template>
<style>
.mfiap0cip {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 3L3 3L3 21L9 21M12 2L12 22M15 3L21 3L21 7M21 9.5L21 14.5M21 17L21 21L15 21");
}

</style>
