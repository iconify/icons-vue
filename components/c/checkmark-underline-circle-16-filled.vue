<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="huzok1_nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:checkmark-underline-circle-16-filled" /></template>
<style>
.huzok1_nz {
  fill: currentColor;
  d: path("M8 14A6 6 0 1 0 8 2a6 6 0 0 0 0 12m2.856-8.85a.52.52 0 0 1 0 .719L7.972 8.85a.484.484 0 0 1-.696 0L6.144 7.68a.52.52 0 0 1 0-.72a.48.48 0 0 1 .696 0l.784.81l2.536-2.62a.48.48 0 0 1 .696 0M6.5 10h2.998a.5.5 0 0 1 0 1H6.5a.5.5 0 0 1 0-1");
}

</style>
