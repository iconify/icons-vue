<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m9fh4xtmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:code-text-16-filled" /></template>
<style>
.m9fh4xtmc {
  fill: currentColor;
  d: path("M1.75 2.5a.75.75 0 0 0 0 1.5h5a.75.75 0 0 0 0-1.5zm3 3a.75.75 0 0 0 0 1.5h3.5a.75.75 0 0 0 0-1.5zM3 9.25a.75.75 0 0 1 .75-.75h7.5a.75.75 0 0 1 0 1.5h-7.5A.75.75 0 0 1 3 9.25M1.75 11.5a.75.75 0 0 0 0 1.5h7a.75.75 0 0 0 0-1.5zm8.75-5.25a.75.75 0 0 1 .75-.75h2a.75.75 0 0 1 0 1.5h-2a.75.75 0 0 1-.75-.75M9.75 2.5a.75.75 0 0 0 0 1.5h4.5a.75.75 0 0 0 0-1.5z");
}

</style>
