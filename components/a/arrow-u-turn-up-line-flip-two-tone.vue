<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_fg4mvrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-u-turn-up-line-flip-two-tone" /></template>
<style>
.b_fg4mvrx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 10L19 12C19 14.7614 16.7614 17 14 17C11.2386 17 9 14.7614 9 12L9 4M5 8L8.6096 3.1877C8.8097 2.9375 9.1903 2.9375 9.3904 3.1877L13 8M4 21L20 21");
}

</style>
