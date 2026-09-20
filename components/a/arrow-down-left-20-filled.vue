<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z9al01-fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-down-left-20-filled" /></template>
<style>
.z9al01-fg {
  fill: currentColor;
  d: path("M12 16.25a.75.75 0 0 1-.75.75h-7.5a.75.75 0 0 1-.75-.75v-7.5a.75.75 0 1 1 1.5 0v5.69L15.72 3.22a.75.75 0 1 1 1.06 1.06L5.56 15.5h5.69a.75.75 0 0 1 .75.75");
}

</style>
