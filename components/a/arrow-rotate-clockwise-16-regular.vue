<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hkz3uccah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-rotate-clockwise-16-regular" /></template>
<style>
.hkz3uccah {
  fill: currentColor;
  d: path("M8 3a5 5 0 0 0-5 5a.5.5 0 0 1-1 0a6 6 0 1 1 9.969 4.5H13a.5.5 0 0 1 0 1h-2.5a.5.5 0 0 1-.5-.5v-2.5a.5.5 0 0 1 1 0V12a5 5 0 0 0-3-9M6 8a2 2 0 1 1 4 0a2 2 0 0 1-4 0m2-1a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

</style>
