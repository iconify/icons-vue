<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jzr20fqxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:ice-cream-fill" /></template>
<style>
.jzr20fqxu {
  fill: currentColor;
  d: path("M208 97.37V96a80 80 0 0 0-160 0v1.37A24 24 0 0 0 56 144h3.29l54.82 95.94a16 16 0 0 0 27.78 0L196.71 144H200a24 24 0 0 0 8-46.63m-61.11 101.57L115.5 144h19.29l21.75 38.06ZM77.71 144h19.36l40.61 71.06L128 232Zm88 21.94L153.21 144h25.08Z");
}

</style>
