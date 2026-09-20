<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j3n646d1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-multiple-person-20-regular" /></template>
<style>
.j3n646d1n {
  fill: currentColor;
  d: path("M15.802 6.627a6.48 6.48 0 0 1 2.199 4.873c0 1.151-.3 2.233-.826 3.172l.796 2.082a1 1 0 0 1-1.204 1.32l-2.487-.697c-.843.4-1.786.623-2.78.623a6.49 6.49 0 0 1-4.926-2.26a7.5 7.5 0 0 0 1.76.257A5.5 5.5 0 0 0 11.5 17a5.5 5.5 0 0 0 2.503-.6l.173-.09l2.86.801l-.969-2.536l.129-.21c.51-.834.804-1.814.804-2.865a5.47 5.47 0 0 0-.963-3.11a7.5 7.5 0 0 0-.236-1.763M8.54 2a6.5 6.5 0 1 1-2.78 12.377l-2.487.697a1 1 0 0 1-1.204-1.32l.796-2.082A6.5 6.5 0 0 1 8.539 2m0 1a5.5 5.5 0 0 0-4.697 8.365l.13.21l-.97 2.536l2.86-.8l.174.088A5.5 5.5 0 1 0 8.539 3m1.71 6c.691 0 1.25.56 1.25 1.25c0 1.25-1 2.25-3 2.25s-3-1-3-2.25C5.5 9.56 6.06 9 6.75 9zM8.5 4.5a1.75 1.75 0 1 1 0 3.5a1.75 1.75 0 0 1 0-3.5");
}

</style>
