<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2itfyboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:diagram-subtask-sharp" /></template>
<style>
.p2itfyboc {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L14 3L14 8L3 8L3 3ZM10 16L21 16L21 21L10 21L10 16ZM6 8L6 18.5L10 18.5");
}

</style>
