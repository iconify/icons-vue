<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="koxs4ndwe"/><path class="w2nnrib4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:clockwise-vertical-arrows" /></template>
<style>
.koxs4ndwe {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M4 36a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4v28a4 4 0 0 1-4 4z");
}

.w2nnrib4r {
  fill: var(--svg-color--fff, #fff);
  d: path("m26 30.2l6-7.2h-4v-8c0-5.523-4.477-10-10-10a9.95 9.95 0 0 0-3.977.827l2.75 3.3A6 6 0 0 1 24 15v8h-4zm-4.023-.026l-2.749-3.301A6 6 0 0 1 12 21v-8h4l-6-7.2L4 13h4v8c0 5.522 4.477 10 10 10a10 10 0 0 0 3.977-.826");
}

</style>
