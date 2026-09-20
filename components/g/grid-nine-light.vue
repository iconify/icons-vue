<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qav1rebhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:grid-nine-light" /></template>
<style>
.qav1rebhe {
  fill: currentColor;
  d: path("M216 50H40a14 14 0 0 0-14 14v128a14 14 0 0 0 14 14h176a14 14 0 0 0 14-14V64a14 14 0 0 0-14-14m-114 96v-36h52v36Zm52 12v36h-52v-36ZM38 110h52v36H38Zm64-12V62h52v36Zm64 12h52v36h-52Zm52-46v34h-52V62h50a2 2 0 0 1 2 2M40 62h50v36H38V64a2 2 0 0 1 2-2m-2 130v-34h52v36H40a2 2 0 0 1-2-2m178 2h-50v-36h52v34a2 2 0 0 1-2 2");
}

</style>
