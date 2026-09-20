<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="g9m568bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:compass-light" /></template>
<style>
.g9m568bmi {
  fill: currentColor;
  d: path("M128 26a102 102 0 1 0 102 102A102.12 102.12 0 0 0 128 26m0 192a90 90 0 1 1 90-90a90.1 90.1 0 0 1-90 90m45.32-143.37l-64 32a6 6 0 0 0-2.69 2.69l-32 64A6 6 0 0 0 80 182a6.06 6.06 0 0 0 2.68-.63l64-32a6 6 0 0 0 2.69-2.69l32-64a6 6 0 0 0-8.05-8.05m-33.79 64.9l-46.11 23.05l23-46.11l46.11-23Z");
}

</style>
