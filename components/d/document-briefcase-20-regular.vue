<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rfzhxt9vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-briefcase-20-regular" /></template>
<style>
.rfzhxt9vl {
  fill: currentColor;
  d: path("M6 2a2 2 0 0 0-2 2v5.05Q4.243 9 4.5 9H5V4a1 1 0 0 1 1-1h4v3.5A1.5 1.5 0 0 0 11.5 8H15v8a1 1 0 0 1-1 1h-3v.5q0 .257-.05.5H14a2 2 0 0 0 2-2V7.414a1.5 1.5 0 0 0-.44-1.06l-3.914-3.915A1.5 1.5 0 0 0 10.586 2zm8.793 5H11.5a.5.5 0 0 1-.5-.5V3.207zM3 11.5v.5h-.5A1.5 1.5 0 0 0 1 13.5v4A1.5 1.5 0 0 0 2.5 19h6a1.5 1.5 0 0 0 1.5-1.5v-4A1.5 1.5 0 0 0 8.5 12H8v-.5A1.5 1.5 0 0 0 6.5 10h-2A1.5 1.5 0 0 0 3 11.5m1.5-.5h2a.5.5 0 0 1 .5.5v.5H4v-.5a.5.5 0 0 1 .5-.5");
}

</style>
