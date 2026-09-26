<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u37__bb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:diagram-successor-sharp" /></template>
<style>
.u37__bb1g {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L12 3L12 8L3 8L3 3ZM3 16L21 16L21 21L3 21L3 16ZM12 5.5L18 5.5L18 12M20.2929 9.7071L18 12L15.7071 9.7071");
}

</style>
