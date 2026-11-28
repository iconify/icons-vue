<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lj1911bmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:border-bottom-sharp-fill" /></template>
<style>
.lj1911bmu {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 17L21 21L3 21L3 17M3 7L3 3L7 3M9.5 3L14.5 3M17 3L21 3L21 7M21 9.5L21 14.5M3 14.5L3 9.5");
}

</style>
