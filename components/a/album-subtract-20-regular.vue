<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qylmo4ifa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:album-subtract-20-regular" /></template>
<style>
.qylmo4ifa {
  fill: currentColor;
  d: path("M5.5 9a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M16 4a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2h-5.6q.244-.476.393-1H16a1 1 0 0 0 1-1V6a1 1 0 0 0-1-1H6v3.022a5.6 5.6 0 0 0-1 0V5H4a1 1 0 0 0-1 1v2.6a5.5 5.5 0 0 0-1 .657V6a2 2 0 0 1 2-2zM3.5 13a.5.5 0 0 0 0 1h4a.5.5 0 0 0 0-1zm10-6A1.5 1.5 0 0 1 15 8.5v1a1.5 1.5 0 0 1-1.5 1.5h-3.1a5.5 5.5 0 0 0-.657-1H13.5a.5.5 0 0 0 .5-.5v-1a.5.5 0 0 0-.5-.5h-4a.5.5 0 0 0-.5.5v.757A5.5 5.5 0 0 0 8 8.6v-.1A1.5 1.5 0 0 1 9.5 7z");
}

</style>
