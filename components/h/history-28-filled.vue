<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="usmfuqfxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:history-28-filled" /></template>
<style>
.usmfuqfxg {
  fill: currentColor;
  d: path("M14 5a8.96 8.96 0 0 0-5.658 2H10a1 1 0 1 1 0 2H6a1 1 0 0 1-1-1.013V4a1 1 0 0 1 2 0v1.514A10.96 10.96 0 0 1 14 3c6.075 0 11 4.925 11 11s-4.925 11-11 11S3 20.075 3 14q0-.555.054-1.099a1 1 0 1 1 1.99.198Q5 13.543 5 14a9 9 0 1 0 9-9m1 3a1 1 0 1 0-2 0v6a1 1 0 0 0 1 1h4a1 1 0 1 0 0-2h-3z");
}

</style>
