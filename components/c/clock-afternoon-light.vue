<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="x5gemcccj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:clock-afternoon-light" /></template>
<style>
.x5gemcccj {
  fill: currentColor;
  d: path("M128 26a102 102 0 1 0 102 102A102.12 102.12 0 0 0 128 26m0 192a90 90 0 1 1 90-90a90.1 90.1 0 0 1-90 90m62-90a6 6 0 0 1-6 6h-41.51l29.75 29.76a6 6 0 1 1-8.48 8.48l-40-40A6 6 0 0 1 128 122h56a6 6 0 0 1 6 6");
}

</style>
