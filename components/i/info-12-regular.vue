<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="e04pcnb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:info-12-regular" /></template>
<style>
.e04pcnb2w {
  fill: currentColor;
  d: path("M5.5 6.5a.5.5 0 0 1 1 0V8a.5.5 0 0 1-1 0zM6 3.75a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5M1 6a5 5 0 1 1 10 0A5 5 0 0 1 1 6m5-4a4 4 0 1 0 0 8a4 4 0 0 0 0-8");
}

</style>
