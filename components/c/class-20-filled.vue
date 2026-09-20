<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w0bvp65yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:class-20-filled" /></template>
<style>
.w0bvp65yt {
  fill: currentColor;
  d: path("M6 2a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2h-3v6.5a.5.5 0 0 1-.8.4L8.5 7.625L6.8 8.9a.5.5 0 0 1-.8-.4zm4 0H7v5.5l1.2-.9a.5.5 0 0 1 .6 0l1.2.9z");
}

</style>
