<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nf60j4t2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-agenda-clock-16-regular" /></template>
<style>
.nf60j4t2o {
  fill: currentColor;
  d: path("M11.5 7a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m0-5A2.5 2.5 0 0 1 14 4.5v2.1a5.5 5.5 0 0 0-1-.392V4.5A1.5 1.5 0 0 0 11.5 3h-7A1.5 1.5 0 0 0 3 4.5v7A1.5 1.5 0 0 0 4.5 13h1.708q.149.524.394 1H4.5A2.5 2.5 0 0 1 2 11.5v-7A2.5 2.5 0 0 1 4.5 2zm0 7a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 .5.5H13a.5.5 0 0 0 0-1h-1V9.5a.5.5 0 0 0-.5-.5m-5.292 1a5.5 5.5 0 0 0-.185 1H5.5a.5.5 0 0 1 0-1zm1.52-2.5a5.5 5.5 0 0 0-.836 1H5.5a.5.5 0 0 1 0-1zM10.5 5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1 0-1z");
}

</style>
