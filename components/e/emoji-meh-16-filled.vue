<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rt6l2dbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:emoji-meh-16-filled" /></template>
<style>
.rt6l2dbld {
  fill: currentColor;
  d: path("M2 8a6 6 0 1 0 12 0A6 6 0 0 0 2 8m5-1a.75.75 0 1 1-1.5 0A.75.75 0 0 1 7 7m3.5 0A.75.75 0 1 1 9 7a.75.75 0 0 1 1.5 0M6 9h4a.5.5 0 0 1 0 1H6a.5.5 0 0 1 0-1");
}

</style>
