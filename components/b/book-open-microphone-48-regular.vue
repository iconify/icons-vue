<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="drka27gnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-open-microphone-48-regular" /></template>
<style>
.drka27gnk {
  fill: currentColor;
  d: path("M44.25 33.25c.69 0 1.25.56 1.25 1.25c0 4.546-3.371 8.303-7.75 8.911v1.339a1.25 1.25 0 1 1-2.5 0v-1.339c-4.379-.608-7.75-4.365-7.75-8.911a1.25 1.25 0 1 1 2.5 0a6.5 6.5 0 1 0 13 0c0-.69.56-1.25 1.25-1.25M20 8c1.602 0 3.037.718 4 1.85A5.24 5.24 0 0 1 28 8h13.25A2.75 2.75 0 0 1 44 10.75v20.51a3.2 3.2 0 0 0-1 .24v-3c0-1.58-.563-3.027-1.5-4.153V10.75a.25.25 0 0 0-.25-.25H28a2.75 2.75 0 0 0-2.75 2.75v21.5c0 .502.137.97.371 1.375c.2 1.349.644 2.617 1.286 3.76A5.25 5.25 0 0 1 24 38.15A5.24 5.24 0 0 1 20 40H6.75A2.75 2.75 0 0 1 4 37.25v-26.5A2.75 2.75 0 0 1 6.75 8zm16.5 16a4.5 4.5 0 0 1 4.5 4.5v6a4.5 4.5 0 1 1-9 0v-6a4.5 4.5 0 0 1 4.5-4.5M6.75 10.5a.25.25 0 0 0-.25.25v26.5c0 .138.112.25.25.25H20a2.75 2.75 0 0 0 2.75-2.75v-21.5A2.75 2.75 0 0 0 20 10.5z");
}

</style>
