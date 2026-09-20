<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rt1k9cy7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:filter-sync-16-filled" /></template>
<style>
.rt1k9cy7l {
  fill: currentColor;
  d: path("M8.5 13a.75.75 0 0 1 0 1.5h-3a.75.75 0 0 1 0-1.5zM6.257 9a5.5 5.5 0 0 0 1.948 1.5H3.5a.75.75 0 0 1 0-1.5zM10.5 1a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m-2 5a.5.5 0 0 0-.5.5V8a.5.5 0 0 0 1 0v-.152a3 3 0 0 0 2.624.183c.373-.15.712-.375.997-.66a.5.5 0 1 0-.707-.707A2 2 0 0 1 9.532 7H10a.5.5 0 0 0 0-1zM5.022 5a5.6 5.6 0 0 0 .069 1.5H1.5a.75.75 0 0 1 0-1.5zM12.5 2.5a.5.5 0 0 0-.5.5v.152a3 3 0 0 0-1.447-.402a3 3 0 0 0-2.174.879a.5.5 0 1 0 .707.707A2 2 0 0 1 11.468 4H11a.5.5 0 0 0 0 1h1.5a.5.5 0 0 0 .5-.5V3a.5.5 0 0 0-.5-.5");
}

</style>
