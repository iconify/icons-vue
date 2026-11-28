<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5_rshqur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clipboard-heart-sharp" /></template>
<style>
.n5_rshqur {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 4L4 4L4 22L20 22L20 4L17 4M7 2L17 2L17 7L7 7ZM12 18C10.175 16.4846 8 15.1806 8 13.2361C8 12.0011 9.0745 11 10.4 11C11 11 11.537 11.2123 12 11.5833C12.463 11.2123 13 11 13.6 11C14.9255 11 16 12.0011 16 13.2361C16 15.1806 13.825 16.4846 12 18Z");
}

</style>
