<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y2hwzpbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:checkmark-circle-32-light" /></template>
<style>
.y2hwzpbqo {
  fill: currentColor;
  d: path("M3 16C3 8.82 8.82 3 16 3s13 5.82 13 13s-5.82 13-13 13S3 23.18 3 16M16 2C8.268 2 2 8.268 2 16s6.268 14 14 14s14-6.268 14-14S23.732 2 16 2m6.854 10.354a.5.5 0 0 0-.708-.708L14.5 19.293l-3.646-3.647a.5.5 0 0 0-.708.708l4 4a.5.5 0 0 0 .708 0z");
}

</style>
