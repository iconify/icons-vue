<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnue5tbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-pin-sharp" /></template>
<style>
.mnue5tbfc {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.5 4L19.5 4L19.5 7L17.5 7L17.5 10.5L22 13.5L22 15L9 15L9 13.5L13.5 10.5L13.5 7L11.5 7L11.5 4ZM15.5 15L15.5 21M1 10L8 10M1 15L6 15M1 20L12 20");
}

</style>
