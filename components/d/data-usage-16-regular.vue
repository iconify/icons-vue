<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k5b65e1bs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-usage-16-regular" /></template>
<style>
.k5b65e1bs {
  fill: currentColor;
  d: path("M3.75 2A1.75 1.75 0 0 0 2 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0 0 14 12.25v-8.5A1.75 1.75 0 0 0 12.25 2zM3 3.75A.75.75 0 0 1 3.75 3h8.5a.75.75 0 0 1 .75.75v8.5a.75.75 0 0 1-.75.75h-8.5a.75.75 0 0 1-.75-.75zM6 6.5a.5.5 0 0 0-1 0v4a.5.5 0 0 0 1 0zM8 8a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-1 0v-2A.5.5 0 0 1 8 8m3-2.5a.5.5 0 0 0-1 0v5a.5.5 0 0 0 1 0z");
}

</style>
