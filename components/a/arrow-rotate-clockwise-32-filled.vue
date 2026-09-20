<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fccv-jb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-rotate-clockwise-32-filled" /></template>
<style>
.fccv-jb4k {
  fill: currentColor;
  d: path("M16 3c7.18 0 13 5.82 13 13c0 4.314-2.103 8.136-5.339 10.5h3.089a1.25 1.25 0 1 1 0 2.5h-6c-.69 0-1.25-.56-1.25-1.25v-6a1.25 1.25 0 1 1 2.5 0v2.864A10.48 10.48 0 0 0 26.5 16c0-5.799-4.701-10.5-10.5-10.5S5.5 10.201 5.5 16A1.25 1.25 0 1 1 3 16C3 8.82 8.82 3 16 3m0 8.5a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m0 2.5a2 2 0 1 0 0 4a2 2 0 0 0 0-4");
}

</style>
