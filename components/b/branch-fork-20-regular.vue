<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n7vqkofzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:branch-fork-20-regular" /></template>
<style>
.n7vqkofzt {
  fill: currentColor;
  d: path("M9 5a3 3 0 1 0-3.5 2.959v4.082a3 3 0 1 0 1 0V11H12a2.5 2.5 0 0 0 2.5-2.5v-.541a3 3 0 1 0-1 0V8.5A1.5 1.5 0 0 1 12 10H6.5V7.959A3 3 0 0 0 9 5M6 7a2 2 0 1 1 0-4a2 2 0 0 1 0 4m0 10a2 2 0 1 1 0-4a2 2 0 0 1 0 4M16 5a2 2 0 1 1-4 0a2 2 0 0 1 4 0");
}

</style>
