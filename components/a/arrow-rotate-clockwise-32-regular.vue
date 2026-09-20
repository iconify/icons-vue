<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k0jufxpcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-rotate-clockwise-32-regular" /></template>
<style>
.k0jufxpcr {
  fill: currentColor;
  d: path("M16 3c7.18 0 13 5.82 13 13c0 4.633-2.425 8.698-6.074 11H27a1 1 0 1 1 0 2h-6a1 1 0 0 1-1-1v-6a1 1 0 1 1 2 0v3.215c3.01-1.962 5-5.355 5-9.215c0-6.075-4.925-11-11-11S5 9.925 5 16a1 1 0 1 1-2 0C3 8.82 8.82 3 16 3m0 9a4 4 0 1 1 0 8a4 4 0 0 1 0-8m0 2a2 2 0 1 0 0 4a2 2 0 0 0 0-4");
}

</style>
