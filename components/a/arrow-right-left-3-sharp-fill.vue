<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q516di87x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-right-left-3-sharp-fill" /></template>
<style>
.q516di87x {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 17L13 17L2.7396 17L2.0856 17M7.1888 11.6995L6.8947 12L2 17L6.8947 22L7.1888 22.3005M10 7L11 7L21.2604 7L21.9144 7M16.8112 12.3005L17.1053 12L22 7L17.1053 2L16.8112 1.6995");
}

</style>
