<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dd96ecbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-rotate-counterclockwise-20-filled" /></template>
<style>
.dd96ecbff {
  fill: currentColor;
  d: path("M10 2.5a7.5 7.5 0 0 1 7.5 7.5a.75.75 0 0 1-1.5 0a6 6 0 1 0-9.5 4.871V13.25a.75.75 0 0 1 1.5 0v3.5a.75.75 0 0 1-.75.75h-3.5a.75.75 0 0 1 0-1.5h1.753A7.5 7.5 0 0 1 10 2.5m0 5a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5M10 9a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

</style>
