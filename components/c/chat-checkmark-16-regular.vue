<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="le8w0obvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-checkmark-16-regular" /></template>
<style>
.le8w0obvo {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1-3.538 13.04l-2.804.935a.5.5 0 0 1-.633-.633l.934-2.806A7 7 0 0 1 8 1m0 1a6 6 0 0 0-5.07 9.207a.5.5 0 0 1 .052.426l-.692 2.075l2.076-.691c.15-.033.29-.034.426.052A6 6 0 1 0 8 2m2.146 4.147a.5.5 0 0 1 .707.707l-3.25 3.25a.5.5 0 0 1-.707 0l-1.75-1.75a.5.5 0 0 1 .707-.707L7.25 9.043z");
}

</style>
