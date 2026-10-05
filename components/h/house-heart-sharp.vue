<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnqdvjoxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:house-heart-sharp" /></template>
<style>
.jnqdvjoxn {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1.6141 11.0785L2 10.7782L12 2.9963L22 10.7782L22.3859 11.0785M4 9.2218L4 21L20 21L20 9.2218M12 17C10.175 15.4846 8 14.1806 8 12.2361C8 11.0011 9.0745 10 10.4 10C11 10 11.537 10.2123 12 10.5833C12.463 10.2123 13 10 13.6 10C14.9255 10 16 11.0011 16 12.2361C16 14.1806 13.825 15.4846 12 17Z");
}

</style>
