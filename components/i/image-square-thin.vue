<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xeijw0b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:image-square-thin" /></template>
<style>
.xeijw0b2y {
  fill: currentColor;
  d: path("M208 36H48a12 12 0 0 0-12 12v160a12 12 0 0 0 12 12h160a12 12 0 0 0 12-12V48a12 12 0 0 0-12-12M44 208V48a4 4 0 0 1 4-4h160a4 4 0 0 1 4 4v87l-31.51-31.52a12 12 0 0 0-17 0L55 212h-7a4 4 0 0 1-4-4m164 4H66.34l102.83-102.83a4 4 0 0 1 5.66 0L212 146.34V208a4 4 0 0 1-4 4M96 116a20 20 0 1 0-20-20a20 20 0 0 0 20 20m0-32a12 12 0 1 1-12 12a12 12 0 0 1 12-12");
}

</style>
