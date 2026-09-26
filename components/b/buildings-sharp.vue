<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyde15b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:buildings-sharp" /></template>
<style>
.zyde15b2q {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 2L22 2L22 22L10 22L10 2ZM10 22L2 22L2 6L10 6M14 5L14 9M14 11L14 15M18 5L18 9M18 11L18 15M6 9L6 13M6 15L6 19M14 22L14 18L18 18L18 22");
}

</style>
