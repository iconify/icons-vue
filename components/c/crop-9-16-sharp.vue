<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuv4zy4xa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:crop-9-16-sharp" /></template>
<style>
.yuv4zy4xa {
  fill: currentColor;
  d: path("M8 20V4h8v16z");
}

</style>
