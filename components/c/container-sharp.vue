<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt5kgkrav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:container-sharp" /></template>
<style>
.zt5kgkrav {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 9L18 9L18 19L2 19L2 9ZM2 9L6 5L22 5L22 15L18 19M18 9L22 5M6 9L6 19M10 9L10 19M14 9L14 19");
}

</style>
