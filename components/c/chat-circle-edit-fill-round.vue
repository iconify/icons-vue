<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-wwwr7vs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-edit-fill-round" /></template>
<style>
.x-wwwr7vs {
  fill: currentColor;
  d: path("M2.954 16.131A9.946 9.946 0 0 1 19.032 4.968A9.945 9.945 0 0 1 7.869 21.046l-4.673.935a1 1 0 0 1-1.177-1.177ZM7 13v3a1 1 0 0 0 1 1h3c.265 0 .52-.105.707-.293l5-5a1 1 0 0 0 0-1.414l-3-3a.997.997 0 0 0-1.414 0l-5 5A1 1 0 0 0 7 13");
}

</style>
