<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="a-q_kibbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chat-circle-slash" /></template>
<style>
.a-q_kibbx {
  fill: currentColor;
  d: path("M53.92 34.62a8 8 0 1 0-11.84 10.76l10.25 11.28a104.06 104.06 0 0 0-16.15 120.22l-11.35 34.05a16 16 0 0 0 20.24 20.24l34.05-11.35a104 104 0 0 0 112.7-9.73l10.26 11.29a8 8 0 1 0 11.84-10.76ZM128 216a87.87 87.87 0 0 1-44.06-11.81a8 8 0 0 0-6.54-.66L40 216l12.47-37.4a8 8 0 0 0-.66-6.54A88 88 0 0 1 63.14 68.54L181 198.23A87.77 87.77 0 0 1 128 216m104-88a104.15 104.15 0 0 1-12.38 49.25a8 8 0 0 1-14.09-7.58A88 88 0 0 0 93.88 46.86a8 8 0 0 1-6.21-14.75A104.06 104.06 0 0 1 232 128");
}

</style>
