<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rjsei07mk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-open-microphone-48-filled" /></template>
<style>
.rjsei07mk {
  fill: currentColor;
  d: path("M44.25 33.25c.69 0 1.25.56 1.25 1.25c0 4.546-3.371 8.303-7.75 8.911v1.339a1.25 1.25 0 1 1-2.5 0v-1.339c-4.379-.608-7.75-4.365-7.75-8.911a1.25 1.25 0 1 1 2.5 0a6.5 6.5 0 1 0 13 0c0-.69.56-1.25 1.25-1.25M20 8c1.576 0 2.997.663 4 1.725A5.5 5.5 0 0 1 28 8h13a3 3 0 0 1 3 3v20.26a3.2 3.2 0 0 0-1 .24v-3a6.48 6.48 0 0 0-2-4.689V11H28a2.5 2.5 0 0 0-2.5 2.5v21c0 1.959.514 3.797 1.411 5.39A5.5 5.5 0 0 1 24 38.276A5.5 5.5 0 0 1 20 40H7a3 3 0 0 1-3-3V11a3 3 0 0 1 3-3zm16.5 16a4.5 4.5 0 0 1 4.5 4.5v6a4.5 4.5 0 1 1-9 0v-6a4.5 4.5 0 0 1 4.5-4.5M7 37h13a2.5 2.5 0 0 0 2.5-2.5v-21A2.5 2.5 0 0 0 20 11H7z");
}

</style>
