<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="b5hyt-h1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-open-lightbulb-28-filled" /></template>
<style>
.b5hyt-h1e {
  fill: currentColor;
  d: path("M23.791 24.794A1.5 1.5 0 0 1 22.321 26h-.641a1.5 1.5 0 0 1-1.471-1.206l-.16-.794h3.901zM11.5 4c.98 0 1.865.402 2.5 1.05A3.5 3.5 0 0 1 16.5 4H24a2 2 0 0 1 2 2v7.528a6 6 0 0 0-2-1.186V6h-7.5A1.5 1.5 0 0 0 15 7.5v13a1.5 1.5 0 0 0 1.5 1.5h1.036c.383.426.824.799 1.314 1.102l.18.898H16.5a3.5 3.5 0 0 1-2.5-1.05A3.5 3.5 0 0 1 11.5 24H4a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2zM22 13a5 5 0 0 1 2.258 9.46l-.109.54h-4.3l-.108-.54A5 5 0 0 1 22 13M4 22h7.5a1.5 1.5 0 0 0 1.5-1.5v-13A1.5 1.5 0 0 0 11.5 6H4z");
}

</style>
