<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ztkv6lbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:hand-palm-bold" /></template>
<style>
.ztkv6lbao {
  fill: currentColor;
  d: path("M188 84a32 32 0 0 0-8 1V60a32 32 0 0 0-43.21-30A32 32 0 0 0 76 44v1a32 32 0 0 0-40 31v76a92 92 0 0 0 184 0v-36a32 32 0 0 0-32-32m8 68a68 68 0 0 1-136 0V76a8 8 0 0 1 16 0v40a12 12 0 0 0 24 0V44a8 8 0 0 1 16 0v64a12 12 0 0 0 24 0V60a8 8 0 0 1 16 0v65.4a52.09 52.09 0 0 0-40 50.6a12 12 0 0 0 24 0a28 28 0 0 1 28-28a12 12 0 0 0 12-12v-20a8 8 0 0 1 16 0Z");
}

</style>
