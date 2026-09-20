<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g503tccsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ios-share-sharp" /></template>
<style>
.g503tccsm {
  fill: currentColor;
  d: path("M4 22V8h5v2H6v10h12V10h-3V8h5v14zm7-6V4.825l-1.6 1.6L8 5l4-4l4 4l-1.4 1.425l-1.6-1.6V16z");
}

</style>
