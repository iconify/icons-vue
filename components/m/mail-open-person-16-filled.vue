<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wo9wg3_lo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-open-person-16-filled" /></template>
<style>
.wo9wg3_lo {
  fill: currentColor;
  d: path("M13.5 11a1.5 1.5 0 0 1 1.5 1.5c0 1.245-1 2.5-3.5 2.5S8 13.75 8 12.5A1.5 1.5 0 0 1 9.5 11zM7.763 9.44a.5.5 0 0 0 .473 0l.503-.27a3 3 0 0 0 .534.84A2.5 2.5 0 0 0 7 12.5q0 .25.038.5H4a2 2 0 0 1-2-2V6.334zM11.5 6a2 2 0 1 1 0 4a2 2 0 0 1 0-4M7.731 1.078a.5.5 0 0 1 .538 0l4.805 3.058c.412.262.707.662.843 1.118l-.632.339A3 3 0 0 0 11.5 5a3 3 0 0 0-3 3q.001.08.007.16L8 8.432L2.086 5.244a2 2 0 0 1 .84-1.108z");
}

</style>
