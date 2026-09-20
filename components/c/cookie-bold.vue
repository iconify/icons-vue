<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qvml-ubtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:cookie-bold" /></template>
<style>
.qvml-ubtp {
  fill: currentColor;
  d: path("M167.31 160.69a16 16 0 1 1-22.62 0a16 16 0 0 1 22.62 0m-86.62-8a16 16 0 1 0 22.62 0a16 16 0 0 0-22.62 0m14.62-33.38a16 16 0 1 0-22.62 0a16 16 0 0 0 22.62 0m48-6.62a16 16 0 1 0 0 22.62a16 16 0 0 0 0-22.62M236 128A108 108 0 1 1 128 20a12 12 0 0 1 12 12a36 36 0 0 0 36 36a12 12 0 0 1 12 12a36 36 0 0 0 36 36a12 12 0 0 1 12 12m-24.67 10.65A60.17 60.17 0 0 1 165 91a60.17 60.17 0 0 1-47.66-46.32a84 84 0 1 0 94 94Z");
}

</style>
