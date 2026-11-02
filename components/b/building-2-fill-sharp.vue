<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ek7drkb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-2-fill-sharp" /></template>
<style>
.ek7drkb0b {
  fill: currentColor;
  d: path("M4 19V4a1 1 0 0 1 1-1h7a1 1 0 0 1 1 1v4.586l.293-.293a1 1 0 0 1 1.414 0l5 5A1 1 0 0 1 20 14v5h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm14-4.586l-4-4l-1 1V19h5Z");
}

</style>
