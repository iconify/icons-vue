<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yqgy4521v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-agenda-clock-16-filled" /></template>
<style>
.yqgy4521v {
  fill: currentColor;
  d: path("M11.5 7a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m0-5A2.5 2.5 0 0 1 14 4.5v2.1c-.75-.383-1.6-.6-2.5-.6a5.48 5.48 0 0 0-3.772 1.5H5.5a.5.5 0 0 0 0 1h1.392a5.5 5.5 0 0 0-.684 1.5H5.5a.5.5 0 0 0 0 1h.523a5.5 5.5 0 0 0 .578 3H4.5A2.5 2.5 0 0 1 2 11.5v-7A2.5 2.5 0 0 1 4.5 2zm0 7a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 .5.5H13a.5.5 0 0 0 0-1h-1V9.5a.5.5 0 0 0-.5-.5m-6-4a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1z");
}

</style>
