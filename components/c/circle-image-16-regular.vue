<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u4qyh8bxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-image-16-regular" /></template>
<style>
.u4qyh8bxs {
  fill: currentColor;
  d: path("M12 6a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2zm-1.47 5.237a.75.75 0 0 0-1.06 0l-1.73 1.729A1 1 0 0 0 8 13h4a1 1 0 0 0 .259-.034zM8 7a1 1 0 0 0-1 1v4q0 .135.034.259l1.729-1.729a1.75 1.75 0 0 1 2.474 0l1.729 1.729A1 1 0 0 0 13 12V8a1 1 0 0 0-1-1zM6.5 1a4.5 4.5 0 0 1 4.472 4H9.964A3.5 3.5 0 1 0 5 8.663v1.08A4.5 4.5 0 0 1 6.5 1m5 6.75a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5");
}

</style>
