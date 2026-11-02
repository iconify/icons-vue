<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdcz7gq1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-dots-fill" /></template>
<style>
.hdcz7gq1u {
  fill: currentColor;
  d: path("M2.954 16.131A9.946 9.946 0 0 1 19.032 4.968A9.945 9.945 0 0 1 7.869 21.046l-4.673.935a1 1 0 0 1-1.177-1.177ZM8 11a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm4 0a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm4.01 0H16a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
