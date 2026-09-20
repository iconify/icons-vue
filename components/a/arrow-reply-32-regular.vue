<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="staonzbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-reply-32-regular" /></template>
<style>
.staonzbyx {
  fill: currentColor;
  d: path("M11.707 6.293a1 1 0 0 1 0 1.414L6.414 13H17c6.627 0 12 5.373 12 12a1 1 0 1 1-2 0c0-5.523-4.477-10-10-10H6.414l5.293 5.293a1 1 0 0 1-1.414 1.414l-7-7a1 1 0 0 1 0-1.414l7-7a1 1 0 0 1 1.414 0");
}

</style>
