<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7i3pnz7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hourglass-end-sharp" /></template>
<style>
.y7i3pnz7k {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 2L21 2M3 22L21 22M6 2L6 7L12 12L18 7L18 2L6 2ZM6 22L6 17L12 12L18 17L18 22L6 22ZM6 18L18 18");
}

</style>
