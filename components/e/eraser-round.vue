<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6x76mbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eraser-round" /></template>
<style>
.b6x76mbju {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m15 16l3-3a4.243 4.243 0 0 0-6-6l-3 3m2 10h10M9 10l6 6m-6-6l-3 3a4.243 4.243 0 0 0 0 6l1 1h4l4-4");
}

</style>
