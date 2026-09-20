<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6rix3b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bucket-check-sharp" /></template>
<style>
.m6rix3b_z {
  fill: currentColor;
  d: path("M5 21L3 7h3V3h12v4h3l-2 14zm5.95-4l4.95-4.95l-1.425-1.4l-3.525 3.525l-1.425-1.425L8.1 14.175zM8 7h8V5H8z");
}

</style>
