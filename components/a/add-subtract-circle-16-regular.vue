<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cu461uk1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:add-subtract-circle-16-regular" /></template>
<style>
.cu461uk1u {
  fill: currentColor;
  d: path("M9 10.5a.5.5 0 0 1 .5-.5H12a.5.5 0 0 1 0 1H9.5a.5.5 0 0 1-.5-.5m-3-6a.5.5 0 0 0-1 0v1H4a.5.5 0 0 0 0 1h1v.8a.5.5 0 0 0 1 0v-.8h1a.5.5 0 0 0 0-1H6zM8 15A7 7 0 1 0 8 1a7 7 0 0 0 0 14m0-1a5.98 5.98 0 0 1-3.874-1.418l8.456-8.456A6 6 0 0 1 8 14m-4.582-2.126a6 6 0 0 1 8.456-8.456z");
}

</style>
