<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmxe-vbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:corner-round-fill-round" /></template>
<style>
.dmxe-vbfo {
  fill: currentColor;
  d: path("M5.179 13.161a15.05 15.05 0 0 1 7.982-7.982A14.8 14.8 0 0 1 19 4a1 1 0 0 1 0 2a12.9 12.9 0 0 0-5.06 1.021a12.9 12.9 0 0 0-4.132 2.787a12.9 12.9 0 0 0-2.787 4.132A12.9 12.9 0 0 0 6 19a1 1 0 0 1-2 0a14.8 14.8 0 0 1 1.179-5.839");
}

</style>
