<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="at6zlacno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:learning-app-16-filled" /></template>
<style>
.at6zlacno {
  fill: currentColor;
  d: path("M11 1H5a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h2.257a5.5 5.5 0 0 1-.657-1H5a1 1 0 0 1-1-1v-.003h2.206A5.5 5.5 0 0 1 13 6.207V3a2 2 0 0 0-2-2M5 3.5h6a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5H5a.5.5 0 0 1-.5-.5V4a.5.5 0 0 1 .5-.5m11 8a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-6 1.495a.5.5 0 0 0 .757.429l2.5-1.497a.5.5 0 0 0 0-.858l-2.5-1.497A.5.5 0 0 0 10 10z");
}

</style>
