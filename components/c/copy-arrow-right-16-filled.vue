<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dp0wws0du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-arrow-right-16-filled" /></template>
<style>
.dp0wws0du {
  fill: currentColor;
  d: path("M11.5 7a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M5 9c0 .89.39 1.688 1.006 2.237A5.5 5.5 0 0 0 6.602 14H4a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h1zm6.854.146a.5.5 0 1 0-.707.708L12.293 11H9.5a.5.5 0 0 0 0 1h2.793l-1.146 1.146a.5.5 0 1 0 .707.707l2.002-2.001a.5.5 0 0 0 .144-.35v-.005a.5.5 0 0 0-.146-.35zM12 2a2 2 0 0 1 2 2v2.6a5.502 5.502 0 0 0-7.771 3.326A2 2 0 0 1 6 9V4a2 2 0 0 1 2-2z");
}

</style>
