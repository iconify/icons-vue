<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mx_-vuqji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:house-play-sharp" /></template>
<style>
.mx_-vuqji {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22.352 11.15L19.998 9.15L11.998 3L3.998 9.15L1.645 11.15M3.998 9.15V21H19.998V9.15M9.498 9.28L15.874 13.5L9.498 17.72V9.28Z");
}

</style>
