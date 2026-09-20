<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t9a9o3big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-line-16-regular" /></template>
<style>
.t9a9o3big {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1 0 14A7 7 0 0 1 8 1M2.022 8.5a5.999 5.999 0 0 0 11.955 0zM8 2a6 6 0 0 0-5.978 5.5h11.955A6 6 0 0 0 8 2");
}

</style>
