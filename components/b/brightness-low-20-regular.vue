<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sk4h5bs4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:brightness-low-20-regular" /></template>
<style>
.sk4h5bs4k {
  fill: currentColor;
  d: path("M10.5 3.5a.5.5 0 0 0-1 0v1a.5.5 0 0 0 1 0zM10 6a4 4 0 1 0 0 8a4 4 0 0 0 0-8m-3 4a3 3 0 1 1 6 0a3 3 0 0 1-6 0m10 0a.5.5 0 0 1-.5.5h-1a.5.5 0 0 1 0-1h1a.5.5 0 0 1 .5.5m-6.5 5.5a.5.5 0 0 0-1 0v1a.5.5 0 0 0 1 0zM5 10a.5.5 0 0 1-.5.5h-1a.5.5 0 0 1 0-1h1a.5.5 0 0 1 .5.5m.854-4.854a.5.5 0 1 0-.708.708l.5.5a.5.5 0 1 0 .708-.708zm-.708 9.708a.5.5 0 0 0 .708 0l.5-.5a.5.5 0 0 0-.708-.708l-.5.5a.5.5 0 0 0 0 .708m9-9.708a.5.5 0 0 1 .708.708l-.5.5a.5.5 0 0 1-.708-.708zm.708 9.708a.5.5 0 0 1-.708 0l-.5-.5a.5.5 0 0 1 .708-.708l.5.5a.5.5 0 0 1 0 .708");
}

</style>
