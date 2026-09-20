<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="x-kz1kb7j"/><path class="gtqgabcol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:letter-o" /></template>
<style>
.gtqgabcol {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.336 17.962c0-6.449 4.341-11.41 10.666-11.41c6.232 0 10.666 5.116 10.666 11.41c0 6.418-4.31 11.41-10.666 11.41c-6.294 0-10.666-4.992-10.666-11.41m16.496 0c0-3.752-1.954-7.131-5.83-7.131s-5.829 3.379-5.829 7.131c0 3.782 1.891 7.132 5.829 7.132s5.83-3.35 5.83-7.132");
}

.x-kz1kb7j {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
