<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eks0l8z4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hourglass-half-sharp" /></template>
<style>
.eks0l8z4f {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 2L21 2M3 22L21 22M6 2L6 7L12 12L18 7L18 2L6 2ZM6 22L6 17L12 12L18 17L18 22L6 22ZM7.2 8L16.8 8M6 18L18 18");
}

</style>
