<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rqhb02bzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-redo-16-filled" /></template>
<style>
.rqhb02bzf {
  fill: currentColor;
  d: path("M13.002 2.75a.75.75 0 0 0-1.5 0v3.095L8.828 3.172a4 4 0 0 0-5.656 5.656l4.95 4.95a.75.75 0 1 0 1.06-1.06l-4.95-4.95a2.5 2.5 0 0 1 3.536-3.536L10.036 6.5H7.75a.75.75 0 0 0 0 1.5h4.4c.47 0 .85-.38.85-.85z");
}

</style>
