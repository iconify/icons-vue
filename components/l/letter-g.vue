<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="x-kz1kb7j"/><path class="jsbc67uyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:letter-g" /></template>
<style>
.jsbc67uyh {
  fill: var(--svg-color--fff, #fff);
  d: path("M25.66 15.915c1.953 0 2.729.992 2.729 2.977c0 5.984-3.906 10.48-10.108 10.48c-6.294 0-10.666-4.992-10.666-11.41c0-6.449 4.341-11.41 10.666-11.41c4.682 0 8.526 2.201 8.526 4.372c0 1.333-.836 2.17-1.922 2.17c-2.108 0-2.542-2.263-6.604-2.263c-3.875 0-5.829 3.379-5.829 7.131c0 3.782 1.892 7.132 5.829 7.132c2.45 0 5.272-1.365 5.272-4.899h-3.164c-1.271 0-2.17-.899-2.17-2.17c0-1.302.992-2.108 2.17-2.108h5.271z");
}

.x-kz1kb7j {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
