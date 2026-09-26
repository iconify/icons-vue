<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te3rrmvax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-rain" /></template>
<style>
.te3rrmvax {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 16L18 16C20.2091 16 22 14.2091 22 12C22 9.7909 20.2091 8 18 8C18 4.6863 15.3137 2 12 2C8.6863 2 6 4.6863 6 8C3.7909 8 2 9.7909 2 12C2 14.2091 3.7909 16 6 16ZM8 20V22M12 20V22M16 20V22");
}

</style>
