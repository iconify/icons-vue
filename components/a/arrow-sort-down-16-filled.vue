<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tixzpccws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-sort-down-16-filled" /></template>
<style>
.tixzpccws {
  fill: currentColor;
  d: path("M7.22 13.78a.75.75 0 0 0 1.06 0l2.75-2.75a.75.75 0 1 0-1.06-1.06L8.5 11.44V2.75a.75.75 0 0 0-1.5 0v8.69L5.53 9.97a.75.75 0 0 0-1.06 1.06z");
}

</style>
