<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e0jncfbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-circle-up-16-filled" /></template>
<style>
.e0jncfbfw {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1 0 14A7 7 0 0 1 8 1m.354 4.646a.5.5 0 0 0-.708 0l-3 3a.5.5 0 1 0 .708.708L8 6.707l2.646 2.647a.5.5 0 1 0 .707-.708z");
}

</style>
