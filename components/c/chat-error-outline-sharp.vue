<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt-i88b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chat-error-outline-sharp" /></template>
<style>
.yt-i88b1i {
  fill: currentColor;
  d: path("m9.4 13.289l2.6-2.581l2.6 2.58l.688-.688l-2.58-2.6l2.58-2.6l-.688-.689L12 9.293l-2.6-2.58l-.689.688l2.581 2.6l-2.58 2.6zM3 20.077V3h18v14H6.077zM5.65 16H20V4H4v13.644zM4 16V4z");
}

</style>
