<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jlsvryb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:drive-train-20-filled" /></template>
<style>
.jlsvryb4v {
  fill: currentColor;
  d: path("M15 2a2 2 0 0 0-2 2v1h-1.585a1.5 1.5 0 0 0-2.83 0H7V4a2 2 0 1 0-4 0v3a2 2 0 1 0 4 0V6h1.585c.151.426.489.764.915.915v6.17a1.5 1.5 0 0 0-.915.915H7v-1a2 2 0 1 0-4 0v3a2 2 0 1 0 4 0v-1h1.585a1.5 1.5 0 0 0 2.83 0H13v1a2 2 0 1 0 4 0v-3a2 2 0 1 0-4 0v1h-1.585a1.5 1.5 0 0 0-.915-.915v-6.17c.426-.151.764-.489.915-.915H13v1a2 2 0 1 0 4 0V4a2 2 0 0 0-2-2");
}

</style>
