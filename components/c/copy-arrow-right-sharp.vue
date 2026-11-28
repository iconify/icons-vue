<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lenho-brs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:copy-arrow-right-sharp" /></template>
<style>
.lenho-brs {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 5L16.0001 2L2 2L2 16.0001L5 16M8 8L22 8L22 22L8 22L8 8ZM11 15L18 15M14.7071 11.7071L18 15L14.7071 18.2929");
}

</style>
