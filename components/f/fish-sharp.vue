<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfvj6mbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fish-sharp" /></template>
<style>
.vfvj6mbph {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12c2-4 5-7 8-7s5 3 6 5l4-4l-2 6l2 6l-4-4c-1 2-3 5-6 5s-6-3-8-7m5-1h.01M12 10c1 1 1 3 0 4");
}

</style>
