<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2z1d9sbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:diagram-predecessor-sharp" /></template>
<style>
.r2z1d9sbg {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 16L12 16L12 21L3 21L3 16ZM3 3L21 3L21 8L3 8L3 3ZM12 18.5L18 18.5L18 12M15.7071 14.2929L18 12L20.2929 14.2929");
}

</style>
