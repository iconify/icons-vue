<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qnqaqr6se"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-reply-32-light" /></template>
<style>
.qnqaqr6se {
  fill: currentColor;
  d: path("M10.854 6.854a.5.5 0 0 0-.708-.708l-7 7a.5.5 0 0 0 0 .708l7 7a.5.5 0 0 0 .708-.708L4.707 14H16.5C22.851 14 28 19.149 28 25.5a.5.5 0 0 0 1 0C29 18.596 23.404 13 16.5 13H4.707z");
}

</style>
