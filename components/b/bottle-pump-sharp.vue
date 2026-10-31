<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azg_aabei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bottle-pump-sharp" /></template>
<style>
.azg_aabei {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 11L18 11L18 22L6 22ZM9 11L9 7L15 7L15 11M12 2L12 7M8 2L13.1716 2C14.9826 2 16.7194 2.7194 18 4L18.2929 4.2929");
}

</style>
