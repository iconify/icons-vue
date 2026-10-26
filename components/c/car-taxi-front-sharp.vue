<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3buy6q6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:car-taxi-front-sharp" /></template>
<style>
.i3buy6q6t {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12L21 12L21 20L3 20ZM5.0513 12L5.35177 11L6 6L18 6L18.6482 11L18.9487 12M8.63617 6L10.5 2L13.5 2L15.3638 6M18 20L19 20L19 22L18 22ZM5 20L6 20L6 22L5 22ZM5.35177 11L2.5 11M18.6482 11L21.5 11M6 16L9 16M15 16L18 16");
}

</style>
