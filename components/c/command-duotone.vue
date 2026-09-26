<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fecg7fbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:command-duotone" /></template>
<style>
.fecg7fbwy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 6L9 18C9 19.6569 7.6569 21 6 21C4.3431 21 3 19.6569 3 18C3 16.3431 4.3431 15 6 15L18 15C19.6569 15 21 16.3431 21 18C21 19.6569 19.6569 21 18 21C16.3431 21 15 19.6569 15 18L15 6C15 4.3431 16.3431 3 18 3C19.6569 3 21 4.3431 21 6C21 7.6569 19.6569 9 18 9L6 9C4.3431 9 3 7.6569 3 6C3 4.3431 4.3431 3 6 3C7.6569 3 9 4.3431 9 6Z");
}

</style>
