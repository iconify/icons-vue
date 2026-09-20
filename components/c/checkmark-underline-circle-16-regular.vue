<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p1oobpb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:checkmark-underline-circle-16-regular" /></template>
<style>
.p1oobpb1y {
  fill: currentColor;
  d: path("M8 13A5 5 0 1 1 8 3a5 5 0 0 1 0 10m0 1A6 6 0 1 0 8 2a6 6 0 0 0 0 12m2.856-8.85a.52.52 0 0 1 0 .719L7.972 8.85a.484.484 0 0 1-.696 0L6.144 7.68a.52.52 0 0 1 0-.72a.48.48 0 0 1 .696 0l.784.81l2.536-2.62a.48.48 0 0 1 .696 0M6 10.5a.5.5 0 0 1 .5-.5h2.998a.5.5 0 0 1 0 1H6.5a.5.5 0 0 1-.5-.5");
}

</style>
