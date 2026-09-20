<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="r_b_xibwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-fat-left-light" /></template>
<style>
.r_b_xibwl {
  fill: currentColor;
  d: path("M208 74h-82V32a6 6 0 0 0-10.24-4.24l-96 96a6 6 0 0 0 0 8.48l96 96A6 6 0 0 0 126 224v-42h82a14 14 0 0 0 14-14V88a14 14 0 0 0-14-14m2 94a2 2 0 0 1-2 2h-88a6 6 0 0 0-6 6v33.51L32.49 128L114 46.49V80a6 6 0 0 0 6 6h88a2 2 0 0 1 2 2Z");
}

</style>
