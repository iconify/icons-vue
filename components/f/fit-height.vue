<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rp7_b024x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fit-height" /></template>
<style>
.rp7_b024x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 2L17 2C18.6569 2 20 3.3431 20 5L20 19C20 20.6569 18.6569 22 17 22L7 22C5.3431 22 4 20.6569 4 19L4 5C4 3.3431 5.3431 2 7 2ZM12 6V18M9 9L12 6L15 9M9 15L12 18L15 15");
}

</style>
