<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb-7vgbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-unfold-more" /></template>
<style>
.mb-7vgbmm {
  fill: currentColor;
  d: path("M12 5.83L15.17 9l1.41-1.41L12 3L7.41 7.59L8.83 9zm0 12.34L8.83 15l-1.41 1.41L12 21l4.59-4.59L15.17 15z");
}

</style>
