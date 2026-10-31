<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhf97rbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:castle" /></template>
<style>
.mhf97rbws {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 8L2 19C2 20.1046 2.8954 21 4 21L20 21C21.1046 21 22 20.1046 22 19L22 8M2 10L22 10M6 10L6 3M18 10L18 3M6 5L18 5M12 5L12 3M15 21L15 16.5C15 15.3954 13.1046 14 12 14C10.8954 14 9 15.3954 9 16.5L9 21");
}

</style>
