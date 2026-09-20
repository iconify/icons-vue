<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="x-kz1kb7j"/><path class="w8yzqsb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:letter-c" /></template>
<style>
.w8yzqsb7t {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.723 6.552c2.264 0 6.666.744 6.666 3.473c0 1.116-.775 2.077-1.922 2.077c-1.272 0-2.139-1.085-4.744-1.085c-3.844 0-5.829 3.256-5.829 7.038c0 3.689 2.015 6.852 5.829 6.852c2.605 0 3.658-1.302 4.93-1.302c1.396 0 2.047 1.395 2.047 2.107c0 2.977-4.682 3.659-6.976 3.659c-6.294 0-10.666-4.992-10.666-11.41c-.001-6.448 4.34-11.409 10.665-11.409");
}

.x-kz1kb7j {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
