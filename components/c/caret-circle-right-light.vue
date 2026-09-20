<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="sxtvksbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:caret-circle-right-light" /></template>
<style>
.sxtvksbxf {
  fill: currentColor;
  d: path("M128 26a102 102 0 1 0 102 102A102.12 102.12 0 0 0 128 26m0 192a90 90 0 1 1 90-90a90.1 90.1 0 0 1-90 90m28.24-94.24a6 6 0 0 1 0 8.48l-40 40a6 6 0 0 1-8.48-8.48L143.51 128l-35.75-35.76a6 6 0 0 1 8.48-8.48Z");
}

</style>
