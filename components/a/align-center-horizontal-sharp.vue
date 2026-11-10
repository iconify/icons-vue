<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2vejrbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-center-horizontal-sharp" /></template>
<style>
.h2vejrbrt {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1 12H4M10 12H14M20 12H23M4 8H10V16H4V8ZM14 4H20V20H14V4Z");
}

</style>
