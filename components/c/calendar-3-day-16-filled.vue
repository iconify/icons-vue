<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x03c_rbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-3-day-16-filled" /></template>
<style>
.x03c_rbto {
  fill: currentColor;
  d: path("M14 11.5a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 11.5v-7A2.5 2.5 0 0 1 4.5 2h7A2.5 2.5 0 0 1 14 4.5zm-8-6a.5.5 0 0 0-1 0v5a.5.5 0 0 0 1 0zm2.5 0a.5.5 0 0 0-1 0v5a.5.5 0 0 0 1 0zm2.5 0a.5.5 0 0 0-1 0v5a.5.5 0 0 0 1 0z");
}

</style>
