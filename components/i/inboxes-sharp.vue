<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_5-6lbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:inboxes-sharp" /></template>
<style>
.a_5-6lbcf {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5475 8L19.4525 8L22 12.155L22 20L6 20L6 12.155ZM6 13H10L12 16H16L18 13H22M2 14L2 8.155L4.5475 4L14.7729 4");
}

</style>
