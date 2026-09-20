<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j8864v7as"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-arrow-down-off-20-filled" /></template>
<style>
.j8864v7as {
  fill: currentColor;
  d: path("M5.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M2.146 2.146a.5.5 0 0 1 .708 0l15 15a.5.5 0 0 1-.707.707l-1.162-1.16A1.5 1.5 0 0 1 14.5 18H9.743A5.5 5.5 0 0 0 4 9.207v-4.5L2.146 2.854a.5.5 0 0 1 0-.708M5.5 12a.5.5 0 0 0-.5.5v2.793l-1.146-1.146a.5.5 0 1 0-.708.707l2.002 2.002a.5.5 0 0 0 .706-.003l2-2a.5.5 0 1 0-.708-.707L6 15.294V12.5a.5.5 0 0 0-.5-.5M10 6.5A1.5 1.5 0 0 0 11.5 8H16v5.879L4.502 2.38c.265-.236.615-.38.998-.38H10zm5.75.5H11.5a.5.5 0 0 1-.5-.5V2.25z");
}

</style>
