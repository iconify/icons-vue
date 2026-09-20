<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="h-j90ewfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-u-right-down-bold" /></template>
<style>
.h-j90ewfd {
  fill: currentColor;
  d: path("m224.49 184.49l-48 48a12 12 0 0 1-17 0l-48-48a12 12 0 1 1 17-17L156 195V88a44 44 0 0 0-88 0v88a12 12 0 0 1-24 0V88a68 68 0 0 1 136 0v107l27.51-27.52a12 12 0 0 1 17 17Z");
}

</style>
