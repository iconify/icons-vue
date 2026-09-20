<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i-xw34bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:connected-32-regular" /></template>
<style>
.i-xw34bfj {
  fill: currentColor;
  d: path("M6.5 4a2.5 2.5 0 1 0 0 5a2.5 2.5 0 0 0 0-5M2 6.5a4.5 4.5 0 1 1 8.31 2.396l3.294 3.294A4.5 4.5 0 0 1 16 11.5c.88 0 1.702.253 2.396.69l3.294-3.294a4.5 4.5 0 1 1 1.414 1.414l-3.294 3.294A4.5 4.5 0 0 1 20.5 16a4.5 4.5 0 0 1-.69 2.396l3.294 3.294a4.5 4.5 0 1 1-1.414 1.414l-3.294-3.294A4.5 4.5 0 0 1 16 20.5a4.5 4.5 0 0 1-2.396-.69l-3.294 3.294a4.5 4.5 0 1 1-1.414-1.414l3.294-3.294A4.5 4.5 0 0 1 11.5 16c0-.88.253-1.702.69-2.396L8.896 10.31A4.5 4.5 0 0 1 2 6.5M25.5 4a2.5 2.5 0 1 0 0 5a2.5 2.5 0 0 0 0-5M4 25.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 0 0-5 0m12-12a2.5 2.5 0 1 0 0 5a2.5 2.5 0 0 0 0-5m7 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 0 0-5 0");
}

</style>
