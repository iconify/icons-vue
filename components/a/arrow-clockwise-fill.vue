<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vxov_sb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-clockwise-fill" /></template>
<style>
.vxov_sb8x {
  fill: currentColor;
  d: path("M240 56v48a8 8 0 0 1-8 8h-48a8 8 0 0 1-5.66-13.66l17-17l-10.55-9.65l-.25-.24a80 80 0 1 0-1.67 114.78a8 8 0 1 1 11 11.63A95.44 95.44 0 0 1 128 224h-1.32a96 96 0 1 1 69.07-164l10.93 10l19.66-19.7A8 8 0 0 1 240 56");
}

</style>
