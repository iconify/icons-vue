<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lw7ne7bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-sort-16-filled" /></template>
<style>
.lw7ne7bfw {
  fill: currentColor;
  d: path("M10.73 13.79c.29.28.75.28 1.04 0l2.75-2.65a.75.75 0 1 0-1.04-1.08L12 11.486V2.75a.75.75 0 0 0-1.5 0v8.736L9.02 10.06a.75.75 0 1 0-1.04 1.08zM5.28 2.22a.75.75 0 0 0-1.06 0L1.47 4.97a.75.75 0 0 0 1.06 1.06L4 4.56v8.69a.75.75 0 0 0 1.5 0V4.56l1.47 1.47a.75.75 0 0 0 1.06-1.06z");
}

</style>
