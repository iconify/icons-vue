<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="nszkq7pfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-reply-all-28-regular" /></template>
<style>
.nszkq7pfl {
  fill: currentColor;
  d: path("M10.28 5.22a.75.75 0 0 1 0 1.06l-5.47 5.47l5.47 5.47a.75.75 0 1 1-1.06 1.06l-6-6a.75.75 0 0 1 0-1.06l6-6a.75.75 0 0 1 1.06 0m4.5 0a.75.75 0 0 1 0 1.06L10.06 11h4.69C20.41 11 25 15.59 25 21.25a.75.75 0 0 1-1.5 0a8.75 8.75 0 0 0-8.75-8.75h-4.69l4.72 4.72a.75.75 0 1 1-1.06 1.06l-6-6a.75.75 0 0 1 0-1.06l6-6a.75.75 0 0 1 1.06 0");
}

</style>
