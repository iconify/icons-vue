<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sctg40b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:album-add-20-filled" /></template>
<style>
.sctg40b0p {
  fill: currentColor;
  d: path("M4 4a2 2 0 0 0-2 2v3.257a5.5 5.5 0 0 1 2-1.05zm12 12h-5.6c.384-.75.6-1.6.6-2.5s-.216-1.75-.6-2.5h3.1A1.5 1.5 0 0 0 15 9.5v-1A1.5 1.5 0 0 0 13.5 7h-4A1.5 1.5 0 0 0 8 8.5v.1a5.5 5.5 0 0 0-3-.578V4h11a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2m-2.5-6H9.743A5.5 5.5 0 0 0 9 9.257V8.5a.5.5 0 0 1 .5-.5h4a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5M10 13.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-4-2a.5.5 0 0 0-1 0V13H3.5a.5.5 0 0 0 0 1H5v1.5a.5.5 0 0 0 1 0V14h1.5a.5.5 0 0 0 0-1H6z");
}

</style>
