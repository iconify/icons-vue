<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="um-yvabjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:anchor" /></template>
<style>
.um-yvabjt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 5C15 6.6569 13.6569 8 12 8C10.3431 8 9 6.6569 9 5C9 3.3431 10.3431 2 12 2C13.6569 2 15 3.3431 15 5ZM12 8L12 22M5.9377 12.9377L4 12.9377C3.4477 12.9377 3 13.3854 3 13.9377C3 13.9792 3.0025 14.0206 3.0077 14.0617C3.5746 18.5968 7.4297 22 12 22C16.5703 22 20.4254 18.5968 20.9923 14.0617C20.9975 14.0206 21 13.9792 21 13.9377C21 13.3854 20.5523 12.9377 20 12.9377L18.0623 12.9377");
}

</style>
