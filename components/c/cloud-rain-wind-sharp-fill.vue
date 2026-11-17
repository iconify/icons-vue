<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng1m6sbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-rain-wind-sharp-fill" /></template>
<style>
.ng1m6sbcj {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.776 16.447L6.224 21.553M13.276 16.447L10.724 21.553M17.776 16.447L15.224 21.553M4.5 16.753L4 16.464C2.762 15.75 2 14.429 2 13C2 10.791 3.791 9 6 9C6 5.686 8.686 3 12 3C15.314 3 18 5.686 18 9C20.209 9 22 10.791 22 13C22 13.823 21.747 14.61 21.296 15.267L20.998 15.7");
}

</style>
