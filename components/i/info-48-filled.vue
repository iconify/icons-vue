<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tw7_nrc9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:info-48-filled" /></template>
<style>
.tw7_nrc9p {
  fill: currentColor;
  d: path("M44 24c0 11.046-8.954 20-20 20S4 35.046 4 24S12.954 4 24 4s20 8.954 20 20m-20-4c-.69 0-1.25.56-1.25 1.25v12.5a1.25 1.25 0 1 0 2.5 0v-12.5c0-.69-.56-1.25-1.25-1.25m0-3a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

</style>
