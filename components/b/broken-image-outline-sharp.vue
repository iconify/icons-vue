<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndgy1mbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:broken-image-outline-sharp" /></template>
<style>
.ndgy1mbog {
  fill: currentColor;
  d: path("M4 20V4h16v16zm2-6.714l4-4l4 4l4-4l1 1V5H5v7.287zM5 19h14v-7.292l-1-1l-4 4l-4-4l-4 4l-1-1zm0 0v-7.292v1V5z");
}

</style>
