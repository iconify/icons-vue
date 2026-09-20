<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="da4knibov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-pause-16-regular" /></template>
<style>
.da4knibov {
  fill: currentColor;
  d: path("M12 10.793V13a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V8.876l4.763 2.564a.5.5 0 0 0 .474 0l1.411-.76q-.587-.21-1.104-.54L7 10.431L2 7.74V7a1 1 0 0 1 1-1h2.022a5.6 5.6 0 0 1 0-1H3a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2v-2.6a5.5 5.5 0 0 1-1 .393M10.5 10a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9m-1-6.5v4a.5.5 0 0 1-1 0v-4a.5.5 0 0 1 1 0m3 0v4a.5.5 0 0 1-1 0v-4a.5.5 0 0 1 1 0");
}

</style>
