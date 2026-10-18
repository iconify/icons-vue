<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nm16lvb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-u-turn-down-line-flip-sharp-two-tone" /></template>
<style>
.nm16lvb3h {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 15L19 12C19 9.2386 16.7614 7 14 7C11.2386 7 9 9.2386 9 12L9 20.6247M4.7809 15.7261L9 21L13.3002 15.6247M3 3L21 3");
}

</style>
