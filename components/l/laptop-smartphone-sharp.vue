<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wg2sg0nmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:laptop-smartphone-sharp" /></template>
<style>
.wg2sg0nmw {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 14L4 2L20 2L20 5M10 18L2 18L2 14L10 14M22 22L22 10L13 10L13 22L22 22ZM16 14L19 14");
}

</style>
