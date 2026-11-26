<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tt4xnpi6u"/><path class="md-_-5bln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:champagne-two-tone" /></template>
<style>
.md-_-5bln {
  d: path("M9 2H15C15.5523 2 16 2.4477 16 3C16 5 17 6.5 17 9C17 12.5 14.8 15 12 15C9.2 15 7 12.5 7 9C7 6.5 8 5 8 3C8 2.4477 8.4477 2 9 2ZM7.4503 6H16.5497M12 15V22M8 22H16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tt4xnpi6u {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.313 13.9588C15.2375 15.2286 13.7156 16 12 16C10.2844 16 8.7625 15.2286 7.687 13.9588C6.6161 12.6947 6 10.9575 6 9C6 7.6112 6.2805 6.5045 6.5338 5.5548C6.7922 4.5855 7 3.8439 7 3C7 1.8954 7.8954 1 9 1L15 1C16.1046 1 17 1.8954 17 3C17 3.8439 17.2078 4.5855 17.4662 5.5548C17.7195 6.5045 18 7.6112 18 9C18 10.9575 17.3839 12.6947 16.313 13.9588Z");
  stroke: none;
}

</style>
