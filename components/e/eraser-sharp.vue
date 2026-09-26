<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnqvqz_ac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:eraser-sharp" /></template>
<style>
.dnqvqz_ac {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.929 3L22 10.071L11.0711 21L7.071 21L2 15.929L14.929 3ZM8 9.9289L15.0711 17M9.071 21L23 21");
}

</style>
