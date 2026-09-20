<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="by9u6ib-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:door-add-16-regular" /></template>
<style>
.by9u6ib-s {
  fill: currentColor;
  d: path("M11.5 7a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M11 1a2 2 0 0 1 2 2v3.208a5.5 5.5 0 0 0-1-.185V3a1 1 0 0 0-1-1H5a1 1 0 0 0-1 1v10a1 1 0 0 0 1 1h1.602q.274.538.656 1H5a2 2 0 0 1-2-2V3a2 2 0 0 1 2-2zm.5 8a.5.5 0 0 0-.5.5V11H9.5a.5.5 0 0 0 0 1H11v1.5a.5.5 0 0 0 1 0V12h1.5a.5.5 0 0 0 0-1H12V9.5a.5.5 0 0 0-.5-.5M6 7a1 1 0 1 1 0 2a1 1 0 0 1 0-2");
}

</style>
