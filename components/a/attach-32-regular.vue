<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a_pcxdfsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:attach-32-regular" /></template>
<style>
.a_pcxdfsj {
  fill: currentColor;
  d: path("M16.223 4.364a8.071 8.071 0 1 1 11.414 11.414l-12.79 12.79a4.89 4.89 0 0 1-6.914-6.915l11.36-11.36a1 1 0 0 1 1.414 1.414l-11.36 11.36a2.89 2.89 0 0 0 4.086 4.086l12.79-12.79a6.071 6.071 0 1 0-8.586-8.585l-13.93 13.93a1 1 0 1 1-1.414-1.414z");
}

</style>
