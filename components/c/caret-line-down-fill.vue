<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vq3a2ac8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:caret-line-down-fill" /></template>
<style>
.vq3a2ac8h {
  fill: currentColor;
  d: path("M42.34 77.66A8 8 0 0 1 48 64h160a8 8 0 0 1 5.66 13.66l-80 80a8 8 0 0 1-11.32 0ZM208 184H48a8 8 0 0 0 0 16h160a8 8 0 0 0 0-16");
}

</style>
