<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="judoelbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-laugh-fill-round" /></template>
<style>
.judoelbiv {
  fill: currentColor;
  d: path("M2.954 16.131A9.946 9.946 0 0 1 19.032 4.968A9.945 9.945 0 0 1 7.869 21.046l-4.673.935a1 1 0 0 1-1.177-1.177ZM9 8a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm6 0a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm1 4H8a1 1 0 0 0-1 1a5 5 0 0 0 1.464 3.536A4.98 4.98 0 0 0 12 18c1.33 0 2.597-.522 3.536-1.464A5 5 0 0 0 17 13a1 1 0 0 0-1-1");
}

</style>
